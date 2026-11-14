<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uch5c30zr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:firewall-server" /></template>
<style>
.uch5c30zr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.8 9.5H2.5v-7H17v6m-5 10.75H2.5v-7h12.2M6 6h.01M6 15.75h.01M18 21.5c-2 0-3.25-1.5-3.25-3.25c0-2 1.75-2.75 2.5-4.75c.75 1 1.25 2 1.25 3q1.125-.75 1.5-1.5c.75 1 1.25 2 1.25 3.25C21.25 20 20 21.5 18 21.5Z");
}

</style>
