<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rzz06fbkf"/><path class="xtsiqbb9n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:home-zap-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rzz06fbkf {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 12L22 20.0002C21.9999 21.657 20.6568 23.0002 19 23.0002L5 23.0002C3.3432 23.0002 2.0001 21.657 2 20.0002L2 11.927C2 11.0454 2.3877 10.208 3.0605 9.6379L10.0605 3.7073C11.0406 2.877 12.4212 2.7739 13.5007 3.3981C13.8098 3.5768 14 3.907 14 4.264L14 8C14 9.6569 15.3431 11 17 11L21 11C21.5523 11 22 11.4477 22 12Z");
  stroke: none;
}

.xtsiqbb9n {
  d: path("M13 4.264C12.2804 3.8481 11.3605 3.9168 10.7072 4.4703L3.7072 10.4009C3.2586 10.7809 3 11.339 3 11.9268L3 20C3 21.1046 3.8954 22 5 22L19 22C20.1046 22 21 21.1046 21 20L21 12M9 22L9 15L15 15L15 22M20 2L17 5L21 5L18 8");
}

</style>
