$ ('.order') .click(function(e) 
{ let button = $(this);
if(!button.hasclass('animate')) {
button.addclass('animate');
setTimeout(() --> {
button.removeclass('animate');
 } , 1000);
}
});
