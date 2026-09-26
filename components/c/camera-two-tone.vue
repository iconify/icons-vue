<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ubjleoo8i"/><path class="dasfx2hmj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:camera-two-tone" /></template>
<style>
.dasfx2hmj {
  d: path("M2 9C2 7.3431 3.3431 6 5 6L7.5 6L8.7 4.4C8.8889 4.1482 9.1852 4 9.5 4L14.5 4C14.8148 4 15.1111 4.1482 15.3 4.4L16.5 6L19 6C20.6569 6 22 7.3431 22 9L22 17C22 18.6569 20.6569 20 19 20L5 20C3.3431 20 2 18.6569 2 17ZM15 13C15 14.6569 13.6569 16 12 16C10.3431 16 9 14.6569 9 13C9 11.3431 10.3431 10 12 10C13.6569 10 15 11.3431 15 13Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ubjleoo8i {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M1 9C1 6.7909 2.7909 5 5 5L7 5L7.9 3.8C8.2777 3.2964 8.8705 3 9.5 3L14.5 3C15.1295 3 15.7223 3.2964 16.1 3.8L17 5L19 5C21.2091 5 23 6.7909 23 9L23 17C23 19.2091 21.2091 21 19 21L5 21C2.7909 21 1 19.2091 1 17Z");
  stroke: none;
}

</style>
