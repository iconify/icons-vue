<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="qc7460ien"/><path class="nki-9-1lf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:banknote-x-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nki-9-1lf {
  d: path("M22.2929 15.7071L15.7071 22.2929M15.7071 15.7071L22.2929 22.2929");
}

.qc7460ien {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2 1L22 1C22.5523 1 23 1.4477 23 2L23 13L13 13L13 17L2 17C1.4477 17 1 16.5523 1 16L1 2C1 1.4477 1.4477 1 2 1ZM15 9C15 7.3431 13.6569 6 12 6C10.3431 6 9 7.3431 9 9C9 10.6569 10.3431 12 12 12C13.6569 12 15 10.6569 15 9ZM16 5L16 7L19 7L19 5L16 5ZM5 11L5 13L8 13L8 11L5 11ZM13 9C13 9.5523 12.5523 10 12 10C11.4477 10 11 9.5523 11 9C11 8.4477 11.4477 8 12 8C12.5523 8 13 8.4477 13 9Z");
  stroke: none;
}

</style>
