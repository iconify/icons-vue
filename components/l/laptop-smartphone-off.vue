<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w5ad4ubvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:laptop-smartphone-off" /></template>
<style>
.w5ad4ubvk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 14L4 4M7.6569 2L18 2C19.1046 2 20 2.8954 20 4M9 18L4 18C2.8954 18 2 17.1046 2 16L2 14.5C2 14.2239 2.2239 14 2.5 14L9 14M22 16.3431L22 13C22 11.3431 20.6569 10 19 10L16 10C15.89 10 15.7813 10.0059 15.6743 10.0175M13 13L13 19C13 20.6569 14.3431 22 16 22L19 22C19.8285 22 20.5785 21.6642 21.1213 21.1213M2 2L22 22");
}

</style>
