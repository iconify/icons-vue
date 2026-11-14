<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lq-t_kbrm"/><path class="mid7pmz3e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:earth-day" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lq-t_kbrm {
  d: path("M3.5 13a8.5 8.5 0 1 0 17 0a8.5 8.5 0 1 0-17 0");
}

.mid7pmz3e {
  d: path("M12 4.5c0-1.75 2-2.5 4.5-2C16 4.25 14 5 12 4.5M4.75 8.75C8.5 9 10 11 9 13c-1 1.5-3 1-5 3m15.25-7.25C16 9.5 14.5 11.5 15.5 14c1 2-1 4-.25 6.75");
}

</style>
