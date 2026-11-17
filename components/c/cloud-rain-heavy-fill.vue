<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvqudr41x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-rain-heavy-fill" /></template>
<style>
.bvqudr41x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2.5359 15C2.1848 14.392 2 13.702 2 13C2 10.791 3.7909 9 6 9C6 5.686 8.6863 3 12 3C15.3137 3 18 5.686 18 9C20.2091 9 22 10.791 22 13C22 13.702 21.8152 14.392 21.4641 15M6 17V21M10 17V21M14 17V21M18 17V21");
}

</style>
