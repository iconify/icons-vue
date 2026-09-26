<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lz7me76fi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bracket-arrow-right-fill" /></template>
<style>
.lz7me76fi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11.1093 4H6C3.79086 4 2 5.79086 2 8V16C2 18.2091 3.79086 20 6 20H11.1093M21.2307 12H11.1093M16.17 6.5L21.8359 11.6314C22.0547 11.8296 22.0547 12.1704 21.8359 12.3686L16.17 17.5");
}

</style>
