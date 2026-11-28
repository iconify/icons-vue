<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ew8w8y77a"/><path clip-rule="evenodd" class="jaqm5vyix"/><path class="rinj_8b-g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clipboard-heart-sharp-duotone" /></template>
<style>
.ew8w8y77a {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 3L20 3C20.5523 3 21 3.4477 21 4L21 22C21 22.5523 20.5523 23 20 23L4 23C3.4477 23 3 22.5523 3 22L3 4C3 3.4477 3.4477 3 4 3Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.jaqm5vyix {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 1L17 1C17.5523 1 18 1.4477 18 2L18 7C18 7.5523 17.5523 8 17 8L7 8C6.4477 8 6 7.5523 6 7L6 2C6 1.4477 6.4477 1 7 1ZM8 3L8 6L16 6L16 3Z");
  stroke: none;
}

.rinj_8b-g {
  d: path("M12 18C10.175 16.4846 8 15.1806 8 13.2361C8 12.0011 9.0745 11 10.4 11C11 11 11.537 11.2123 12 11.5833C12.463 11.2123 13 11 13.6 11C14.9255 11 16 12.0011 16 13.2361C16 15.1806 13.825 16.4846 12 18Z");
}

</style>
