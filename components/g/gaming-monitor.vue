<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y2gdn_s4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gaming-monitor" /></template>
<style>
.y2gdn_s4o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.9 14H2.5V2.5h19v10.1M9.5 14v4.5m-3.5 0h4.7m5.05-3.5h3.75a2.25 2.25 0 0 1 2.25 2.25V21l-2.25-1.5h-3.75L13.5 21v-3.75A2.25 2.25 0 0 1 15.75 15Zm-.25 2.5H17m2.5 0h.01");
}

</style>
