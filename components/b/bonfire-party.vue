<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mznek3bvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bonfire-party" /></template>
<style>
.mznek3bvm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75c3 2.5 5 5 5 8a5 5 0 0 1-10 0c0-1.5.75-3 2-4c.25 1.25 1 2 2 2.25c-.5-2.25 0-4.25 1-6.25m-7.75 14l15.5 4.5m-15.5 0l15.5-4.5");
}

</style>
