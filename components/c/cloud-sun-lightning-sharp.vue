<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxvu1abig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cloud-sun-lightning-sharp" /></template>
<style>
.rxvu1abig {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.16 14.1a3.02 3.02 0 0 1-.41-6.02a4.35 4.35 0 0 1 8.05-1.04a3.4 3.4 0 0 1-.45 7.06ZM4.84 8.67L3.704 4.612l4.106.948M3.5 8h-.75M4.6 5.35l-.53-.53m3.18-.57V3.5m6.5 13.25l-2.25 2.5h3.25l-2 2");
}

</style>
