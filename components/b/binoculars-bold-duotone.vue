<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y5pxau-ez"/><path class="c6jusnpnu"/><path class="z4wn6twxq"/><path class="rj54wxb9c"/><g class="xtpeb-edw"><path class="g3sj8mbxp"/><path class="pxoue4g9a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:binoculars-bold-duotone" /></template>
<style>
.c6jusnpnu {
  fill: currentColor;
  d: path("M22.0586 18.25C22.0456 18.9015 22.0238 19.4489 22.0107 19.75H14V18.25H22.0586Z");
}

.g3sj8mbxp {
  d: path("M8.73347 2H6.99982C5.49982 2 5.23028 2.77865 4.99982 4C4.76936 5.22135 2.35967 10.5619 1.99982 15C1.84202 16.9462 1.99982 20 1.99982 20C1.99982 21.1046 2.89525 22 3.99982 22H7.99982C9.10439 22 9.99982 21.1046 9.99982 20V4C9.99982 2.89543 9.83804 2 8.73347 2Z");
}

.pxoue4g9a {
  d: path("M15.2665 2H17.0002C18.5002 2 18.7697 2.77865 19.0002 4C19.2306 5.22135 21.6403 10.5619 22.0002 15C22.158 16.9462 22.0002 20 22.0002 20C22.0002 21.1046 21.1047 22 20.0002 22H16.0002C14.8956 22 14.0002 21.1046 14.0002 20V4C14.0002 2.89543 14.162 2 15.2665 2Z");
}

.rj54wxb9c {
  fill: currentColor;
  d: path("M14 9.75H10V8.25H14V9.75Z");
}

.xtpeb-edw {
  fill: currentColor;
  opacity: var(--svg-opacity--0-5, 0.5);
}

.y5pxau-ez {
  fill: currentColor;
  d: path("M10 19.75H1.98926C1.97618 19.4489 1.95438 18.9015 1.94141 18.25H10V19.75Z");
}

.z4wn6twxq {
  fill: currentColor;
  d: path("M14 15.75H10V14.25H14V15.75Z");
}

</style>
