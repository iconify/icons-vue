<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="q9o8lbcru"/><path class="fty2m02rz"/><path class="oiaxhzy4f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:angry-react" /></template>
<style>
.fty2m02rz {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 11.5h.01m4.99 0h.01");
}

.oiaxhzy4f {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 15.25h4.5");
}

.q9o8lbcru {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.3 19.43a8.75 8.75 0 1 0-4.23-4.23l-.67 4.35c-.1.6.45 1.1 1 .95ZM7.75 8.25L10.5 9.5m5.75-1.25L13.5 9.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
