<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="bf47hqmwa"/><path class="e8pp1r4ql"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-check-sharp-duotone" /></template>
<style>
.bf47hqmwa {
  stroke-opacity: 0.4;
  d: path("M5.7508 17.0673L5 16.874C3.2748 16.4299 2 14.8638 2 13C2 10.7909 3.7909 9 6 9C6 5.6863 8.6863 3 12 3C15.3137 3 18 5.6863 18 9C20.2091 9 22 10.7909 22 13C22 14.8638 20.7252 16.4299 19 16.874L18.2492 17.0673");
}

.e8pp1r4ql {
  d: path("M8.7071 18.7071L9 19L11 21L15 17L15.2929 16.7071");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
