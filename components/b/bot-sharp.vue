<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="k14ve0bcc"/><path class="sp3ujwwyq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bot-sharp" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.k14ve0bcc {
  d: path("M4 8L20 8L20 21L4 21L4 8ZM12 8L12 3.5M1 14.5L4 14.5M23 14.5L20 14.5M9 11L9 14M15 11L15 14M8 17L16 17");
}

.sp3ujwwyq {
  fill: currentColor;
  d: path("M13.5 3.5C13.5 4.3284 12.8284 5 12 5C11.1716 5 10.5 4.3284 10.5 3.5C10.5 2.6716 11.1716 2 12 2C12.8284 2 13.5 2.6716 13.5 3.5Z");
  stroke: none;
}

</style>
