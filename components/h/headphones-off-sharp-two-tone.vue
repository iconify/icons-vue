<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="bty7mpj8n"/><path class="keaa46byq"/><path class="itmzxabip"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:headphones-off-sharp-two-tone" /></template>
<style>
.bty7mpj8n {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 12C2 10.4812 3.4812 9 5 9H7C7.5523 9 8 9.4477 8 10V21C8 21.5523 7.5523 22 7 22H5C3.4812 22 2 20.5188 2 19V12Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.itmzxabip {
  d: path("M3 12C3 10.8954 3.8954 10 5 10H7V21H5C3.8954 21 3 20.1046 3 19V12ZM3 12C3 9.5147 4.0074 7.2647 5.636 5.636M20.4142 20.4142C20.0523 20.7761 19.5523 21 19 21H17V17M1.7071 1.7071L22.2929 22.2929");
}

.keaa46byq {
  stroke-opacity: 0.4;
  d: path("M17 12.3431V10H19C20.1046 10 21 10.8954 21 12M21 12V16.34M21 12C21 7.0294 16.9706 3 12 3C10.9949 3 10.0282 3.1648 9.1256 3.4688L8.1779 3.788");
}

</style>
