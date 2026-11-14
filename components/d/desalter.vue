<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v6am1qbgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:desalter" /></template>
<style>
.v6am1qbgu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 3.5h9.5a3.75 3.75 0 0 1 3.75 3.75A3.75 3.75 0 0 1 15.75 11h-9.5A3.75 3.75 0 0 1 2.5 7.25A3.75 3.75 0 0 1 6.25 3.5M4.5 11l-.75 4H7.5l-.75-4m4.75 0l-.75 4h2.83m.739-.964L13.75 11M18 14c1.5 1.75 3 3 3 4.75a3 3 0 0 1-6 0c0-1.75 1.5-3 3-4.75");
}

</style>
