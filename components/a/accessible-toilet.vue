<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fylsv6r9h"/><path class="tsvp5r5pl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:accessible-toilet" /></template>
<style>
.fylsv6r9h {
  d: path("M5.5 2.5zA2.5 2.5 0 0 1 8 5v3a2.5 2.5 0 0 1-2.5 2.5A2.5 2.5 0 0 1 3 8V5a2.5 2.5 0 0 1 2.5-2.5m8.258 11.605c-.818.983-1.972 1.638-3.258 1.895l.5 4H5.5l.5-4.5c-1.75-1-3-2.75-3-5h12c0 .69-.106 1.327-.299 1.905M14 19a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tsvp5r5pl {
  d: path("M16.5 14.5V19h2.75L21 21.5");
}

</style>
