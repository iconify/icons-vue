<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dzrcwnbly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:boom-arm" /></template>
<style>
.dzrcwnbly {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3.5h15M7 3.5v15M3 20a4 1.5 0 1 0 8 0a4 1.5 0 1 0-8 0M18.5 3.5v4m-.77 0h1.54a1.5 1.5 0 0 1 1.471 1.206l.4 2A1.5 1.5 0 0 1 19.67 12.5h-2.34a1.5 1.5 0 0 1-1.471-1.794l.4-2A1.5 1.5 0 0 1 17.73 7.5");
}

</style>
