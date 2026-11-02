<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gj2u3m68c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cloud-sync-corner-sharp" /></template>
<style>
.gj2u3m68c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 19A5 5 0 0 1 7 9c1.819-6.366 9.638-6.116 11 0m1 4a4.472 4.472 0 0 1 0 8m3 0h-3v-3m-4 3a4.472 4.472 0 0 1 0-8m-3 0h3v3");
}

</style>
