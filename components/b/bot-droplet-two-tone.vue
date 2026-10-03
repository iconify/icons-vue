<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ioj8z8i5q"/><path class="nvps3ac9h"/><path class="f_m71knqm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bot-droplet-two-tone" /></template>
<style>
.f_m71knqm {
  d: path("M10 11.6028L10.4521 14.5685M13.9543 11L14.4064 13.9657");
}

.ioj8z8i5q {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19.2 8.6C20.3684 10.1579 21 12.0527 21 14C21 18.9706 16.9706 23 12 23C7.0294 23 3 18.9706 3 14C3 12.0527 3.6316 10.1579 4.8 8.6L9.6 2.2C10.1666 1.4446 11.0557 1 12 1C12.9443 1 13.8334 1.4446 14.4 2.2L19.2 8.6Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nvps3ac9h {
  d: path("M18.4 9.2C19.4386 10.5848 20 12.269 20 14C20 18.4183 16.4183 22 12 22C7.5817 22 4 18.4183 4 14C4 12.269 4.5614 10.5848 5.6 9.2L10.4 2.8C10.7777 2.2964 11.3705 2 12 2C12.6295 2 13.2223 2.2964 13.6 2.8L18.4 9.2Z");
}

</style>
