<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="w04b_obqj"/><path class="yoq2lwz2y"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gyen-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.w04b_obqj {
  fill: var(--svg-color--005bac, #005bac);
  d: path("M24 0H0v24h24z");
}

.yoq2lwz2y {
  fill: var(--svg-color--fff, #fff);
  d: path("M20 12c0 2.652-3.58 4.8-8 4.8S4 14.652 4 12s3.58-4.8 8-4.8c2.96 0 5.548.964 6.928 2.4H15.66c-.88-.736-2.192-1.2-3.66-1.2c-2.652 0-4.8 1.52-4.8 3.4s2.148 3.4 4.8 3.4c2.16 0 3.988-1.012 4.588-2.4h-4.6a.795.795 0 0 1-.788-.8c0-.44.352-.8.792-.8h7.896q.113.391.112.8");
}

</style>
