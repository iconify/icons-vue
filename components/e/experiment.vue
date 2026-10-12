<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ru_30hssv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:experiment" /></template>
<style>
.ru_30hssv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 4.25h3.5v5.1l4.35 8.1a2.25 2.25 0 0 1-1.95 3.35h-8.3a2.25 2.25 0 0 1-1.95-3.35l4.35-8.1ZM6.25 15h6.5M17.5 2.75q.45 3.3 3.75 3.75q-3.3.45-3.75 3.75q-.45-3.3-3.75-3.75q3.3-.45 3.75-3.75");
}

</style>
