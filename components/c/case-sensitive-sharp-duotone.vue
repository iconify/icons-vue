<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="h608s2btr"/><path class="if1dw7xvm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:case-sensitive-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.h608s2btr {
  stroke-opacity: 0.4;
  d: path("M1.93 18.627L7.002 6L12.074 18.627M4.19 13H9.813");
}

.if1dw7xvm {
  d: path("M22 10V19M22 15C22 16.657 20.657 18 19 18C17.343 18 16 16.657 16 15C16 13.343 17.343 12 19 12C20.657 12 22 13.343 22 15Z");
}

</style>
