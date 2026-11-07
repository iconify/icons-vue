<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="owidc8bjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:list-restart-duotone" /></template>
<style>
.owidc8bjr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 6h11M3 11h5m-5 5h5m4 1a4.472 4.472 0 1 0 0-4m3 0h-3v-3");
}

</style>
