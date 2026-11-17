<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="wkwtiabaf"/><path class="vnkmgc73g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-fog-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vnkmgc73g {
  d: path("M7 17H17M4 21H11M13 21H20");
}

.wkwtiabaf {
  stroke-opacity: 0.4;
  d: path("M4.5 16.7528L4 16.4641C2.762 15.7496 2 14.4291 2 13C2 10.7909 3.791 9 6 9C6 5.6863 8.686 3 12 3C15.314 3 18 5.6863 18 9C20.209 9 22 10.7909 22 13C22 14.4291 21.238 15.7496 20 16.4641L19.5 16.7528");
}

</style>
