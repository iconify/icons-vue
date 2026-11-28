<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="vajaifl3o"/><path class="aslqjgb8d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clipboard-off-sharp-duotone" /></template>
<style>
.aslqjgb8d {
  d: path("M1.707 1.7071L22.293 22.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vajaifl3o {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 21.12V22C21 22.5523 20.552 23 20 23H4C3.448 23 3 22.5523 3 22V4C3 3.7544 3.088 3.5295 3.235 3.3554L21 21.12ZM6 2.3431V2C6 1.4477 6.448 1 7 1H17C17.552 1 18 1.4477 18 2V3H20C20.552 3 21 3.4477 21 4V17.3431L9.657 6H16V3H8V4.3431L6 2.3431Z");
  stroke: none;
}

</style>
