<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="zwnq0nbdv"/><path class="f7d702b9j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:broadcast-sharp-fill" /></template>
<style>
.f7d702b9j {
  fill: currentColor;
  d: path("M13 9C13 9.5523 12.5523 10 12 10C11.4477 10 11 9.5523 11 9C11 8.4477 11.4477 8 12 8C12.5523 8 13 8.4477 13 9Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zwnq0nbdv {
  d: path("M9.297 12.1135L8.7234 11.2943C8.2526 10.6219 8 9.8209 8 9C8 8.1791 8.2526 7.3781 8.7234 6.7057L9.297 5.8865M14.703 5.8865L15.2766 6.7057C15.7474 7.3781 16 8.1791 16 9C16 9.8209 15.7474 10.6219 15.2766 11.2943L14.703 12.1135M7.4585 15.6614L6.7085 15C4.9865 13.4813 4 11.296 4 9C4 6.704 4.9865 4.5187 6.7085 3L6.992 2.75M17.008 2.75L17.2915 3C19.0135 4.5187 20 6.704 20 9C20 11.296 19.0135 13.4813 17.2915 15L16.5415 15.6614M12 13L12 22");
}

</style>
