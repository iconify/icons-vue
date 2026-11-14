<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cyxnj579s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:crucifix-standing" /></template>
<style>
.cyxnj579s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 15.5V9h-4V6h4V2.5h3V6h4v3h-4v6.5m-4.75 0h6.5A1.75 1.75 0 0 1 17 17.25v2.5a1.75 1.75 0 0 1-1.75 1.75h-6.5A1.75 1.75 0 0 1 7 19.75v-2.5a1.75 1.75 0 0 1 1.75-1.75");
}

</style>
