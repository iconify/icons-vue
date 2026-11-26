<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_zirjbof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:armchair-sharp" /></template>
<style>
.r_zirjbof {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 11L4 2L20 2L20 11M19 20L19 22L19 23M5 20L5 22L5 23M2 20L22 20L22 13C22 11.8954 21.1046 11 20 11C18.8954 11 18 11.8954 18 13L18 14L6 14L6 13C6 11.8954 5.1046 11 4 11C2.8954 11 2 11.8954 2 13Z");
}

</style>
