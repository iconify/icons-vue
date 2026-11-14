<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xpfllebqo"/><path class="gunvsmbvn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:body-lotion" /></template>
<style>
.gunvsmbvn {
  d: path("M12 12.75s1.5 1.75 1.5 2.75a1.5 1.5 0 0 1-3 0c0-1 1.5-2.75 1.5-2.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xpfllebqo {
  d: path("M10.875 10.5h2.25a4.375 4.375 0 0 1 4.375 4.375v1.75A4.375 4.375 0 0 1 13.125 21h-2.25A4.375 4.375 0 0 1 6.5 16.625v-1.75a4.375 4.375 0 0 1 4.375-4.375m-.875 0V8h4v2.5M12 8V4.5h4");
}

</style>
