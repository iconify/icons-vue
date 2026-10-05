<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dorv6lczq"/><path class="ageaa2buq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-x-two-tone" /></template>
<style>
.ageaa2buq {
  d: path("M9 15L15 21M15 15L9 21");
}

.dorv6lczq {
  stroke-opacity: 0.4;
  d: path("M5 16.874C3.2748 16.4299 2 14.8638 2 13C2 10.7909 3.7909 9 6 9C6 5.6863 8.6863 3 12 3C15.3137 3 18 5.6863 18 9C20.2091 9 22 10.7909 22 13C22 14.8638 20.7252 16.4299 19 16.874");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
