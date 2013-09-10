[portfolio2013-Lightbox](http://jbutz.github.io/bootstrap-lightbox/) 
=============

The LightBox Problem in the Logo Design section


Quick Start
=============
was Following the Plugin steps. 1) Have trouble to make the lightbox popup. 2) How to add control Next and Previous? Make all the images as an [Image Set] (http://lokeshdhakar.com/projects/lightbox2/) 

HTML
=============

    <!-- Web Layout SECTION ================================================== -->
    <div class="main"></div>
    <div class="jumbotron">
    <div class="container">
      <h4> Web Page Design Here</h4>
    </div>
    </div>

    <!-- Logo SECTION ================================================== -->
    <div class="maincontainer" id="gallery">
    <div class="container">
      <div class="row">
      <div class="col-md-12">
        <h2> Logo Design</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc metus lacus, scelerisque eget consectetur sit amet, porta nec nisl. Nunc elementum bibendum ligula. Mauris ultricies est at ornare sagittis. Mauris ultricies vulputate volutpat. Morbi venenatis nisi vestibulum lacus eleifend, id porta lorem vulputate. Suspendisse cursus massa vitae porta laoreet. Etiam leo diam, consectetur fermentum lacinia nec, aliquam sed metus. Duis est lorem, rutrum in suscipit sit amet, vestibulum at augue. Nullam lacus odio, blandit eget euismod eget, sagittis et mi. Fusce quis imperdiet lacus. </p>
      </div>


      
      <div class="col-xs-6 col-sm-6 col-md-3">
       <div id="demoLightbox" class="lightbox hide fade" tabindex="-1" role="dialog" aria-hidden="true">
          <div class="lightbox-content">
          <img src="img/logoimage.jpg" />
          <div class="lightbox-caption">
          <p>This is my background image</p>
          </div>
          </div>
        </div>
                
          <a data-toggle="lightbox" href="#demoLightbox" class="thumbnail">
            <img src="img/logothumb.jpg" />
          </a>
      </div>
