<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cb_5mybpz"/><path class="l4qa6rb_p"/><path class="a3xey_y6d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:loading-gear" /></template>
<style>
.a3xey_y6d {
  d: path("M20.75 4.75L20 7.5l-2.75-.75m-14 12.5L4 16.5l2.75.75");
}

.cb_5mybpz {
  d: path("M11.084 6.581za.87.87 0 0 1 .864-.775h.104a.87.87 0 0 1 .864.775a1.32 1.32 0 0 0 .804 1.074l.136.056a1.32 1.32 0 0 0 1.328-.19a.87.87 0 0 1 1.159.062l.074.074a.87.87 0 0 1 .062 1.159a1.32 1.32 0 0 0-.19 1.328l.056.136a1.32 1.32 0 0 0 1.074.804a.87.87 0 0 1 .775.864v.104a.87.87 0 0 1-.775.864a1.32 1.32 0 0 0-1.074.804l-.056.136a1.32 1.32 0 0 0 .19 1.328a.87.87 0 0 1-.062 1.159l-.074.074a.87.87 0 0 1-1.159.062a1.32 1.32 0 0 0-1.328-.19l-.136.056a1.32 1.32 0 0 0-.804 1.074a.87.87 0 0 1-.864.775h-.104a.87.87 0 0 1-.864-.775a1.32 1.32 0 0 0-.804-1.074l-.136-.056a1.32 1.32 0 0 0-1.328.19a.87.87 0 0 1-1.159-.062l-.074-.074a.87.87 0 0 1-.062-1.159a1.32 1.32 0 0 0 .19-1.328l-.056-.136a1.32 1.32 0 0 0-1.074-.804a.87.87 0 0 1-.775-.864v-.104a.87.87 0 0 1 .775-.864a1.32 1.32 0 0 0 1.074-.804l.056-.136a1.32 1.32 0 0 0-.19-1.328a.87.87 0 0 1 .062-1.159l.074-.074a.87.87 0 0 1 1.159-.062a1.32 1.32 0 0 0 1.328.19l.136-.056a1.32 1.32 0 0 0 .804-1.074");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l4qa6rb_p {
  d: path("M10.25 12a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M3.989 7.375a9.25 9.25 0 0 1 16.022 0m0 9.25a9.25 9.25 0 0 1-16.022 0");
}

</style>
