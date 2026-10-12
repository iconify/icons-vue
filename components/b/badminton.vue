<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xmny-1b8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:badminton" /></template>
<style>
.xmny-1b8b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 3.25h10q1.25 0 .89 1.2l-2.78 9.1q-.36 1.2-1.61 1.2h-3q-1.25 0-1.61-1.2l-2.78-9.1q-.36-1.2.89-1.2m3 2.5l.75 6.5M14 5.75l-.75 6.5m-4 5h5.5v1.25a2.75 2.75 0 0 1-5.5 0Z");
}

</style>
