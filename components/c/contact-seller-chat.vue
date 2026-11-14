<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hmyfpbilo"/><path class="m2mmmgbee"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:contact-seller-chat" /></template>
<style>
.hmyfpbilo {
  d: path("M3 6.5V14a2.5 2.5 0 0 0 2.5 2.5H7V20l4-3.5h7.5A2.5 2.5 0 0 0 21 14V6.5m-18 0L4.5 3h15L21 6.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m2mmmgbee {
  d: path("M3 6.5a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0m-12.5 6h.01m3.49 0h.01m3.49 0h.01");
}

</style>
