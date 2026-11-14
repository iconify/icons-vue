<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqk8st1bz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:game-server" /></template>
<style>
.aqk8st1bz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 2.5h16v4H3Zm13.4 10.75H3v-4h16v3.9M11.2 20H3v-4h8.8M6.5 4.5h.01m-.01 6.75h.01M16.5 16h3a2.5 2.5 0 0 1 2.5 2.5V20a1.5 1.5 0 0 1-2.25 1.25L19 20.5h-2l-.75.75A1.5 1.5 0 0 1 14 20v-1.5a2.5 2.5 0 0 1 2.5-2.5Z");
}

</style>
