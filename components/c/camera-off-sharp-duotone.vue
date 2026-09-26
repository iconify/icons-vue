<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="k22l5nm1h"/><path class="uwftcyb8e"/><path class="v8h5vrbeb"/><path class="ysqxkebtz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:camera-off-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.k22l5nm1h {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 5L9.71484 9.71484C8.67982 10.4362 8.00013 11.6383 8 12.999C8 15.2082 9.79082 16.999 12 16.999C13.3611 16.999 14.5618 16.3185 15.2832 15.2832L21 21H2C1.4477 21 1 20.5523 1 20V6C1 5.4477 1.4477 5 2 5H5Z");
  stroke: none;
}

.uwftcyb8e {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15 3C15.3147 3.00003 15.6109 3.14862 15.7998 3.40039L17 5H22C22.5523 5 23 5.4477 23 6V19.3428L7.70996 4.05273L8.2002 3.40039C8.38908 3.14862 8.68534 3.00003 9 3H15Z");
  stroke: none;
}

.v8h5vrbeb {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14.5605 14.5605L13.709 14.04C13.3562 14.6176 12.722 14.999 12 14.999C10.8954 14.999 10 14.1036 10 12.999C10.0001 12.2773 10.3818 11.6438 10.959 11.291L10.4385 10.4385L14.5605 14.5605Z");
  stroke: none;
}

.ysqxkebtz {
  d: path("M1.70709 1.70703L22.2929 22.2928");
}

</style>
