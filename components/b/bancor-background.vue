<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="q1q-0sb3i"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bancor-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q1q-0sb3i {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.185 4L7.19 6.309l3.995 2.32l3.996-2.32zm-4.532 7.848l3.986 2.301V9.542L6.653 7.24zm0 5.851L10.639 20v-4.607l-3.986-2.301zm9.064-5.851l-3.986 2.301V9.542l3.986-2.301zm1.63.302v4.609L11.731 20v-4.607z");
}

</style>
