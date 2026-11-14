<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3nd6cc2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bus-stop-ad" /></template>
<style>
.i3nd6cc2q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 6.5l2.25-3h13.5l2.25 3Zm2 0V21M19 6.5V21M7.75 9.25h8.5v9.5h-8.5Z");
}

</style>
