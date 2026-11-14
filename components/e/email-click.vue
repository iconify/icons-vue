<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o68afs8cp"/><path class="yc1fu_b7j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:email-click" /></template>
<style>
.o68afs8cp {
  d: path("M12 18H2.5V4h19v14h-2.2M2.5 6l4.147 1.746m5.622 2.141L21.5 6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yc1fu_b7j {
  d: path("m12.5 13l6.25 2.5L16 16l-.5 2.75Z");
}

</style>
