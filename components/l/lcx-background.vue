<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="zf7w4o3qi"/><path class="avyxj0nff"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lcx-background" /></template>
<style>
.avyxj0nff {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.5 6.5V4L12 8.455L16.5 4v2.5L12 11zm0 11V20l4.5-4.455L16.5 20v-2.5L12 13zm10-1H20L15.545 12L20 7.5h-2.5L13 12zm-11 0H4L8.455 12L4 7.5h2.5L11 12z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.zf7w4o3qi {
  fill: var(--svg-color--5e5e5e, #5e5e5e);
  d: path("M24 0H0v24h24z");
}

</style>
