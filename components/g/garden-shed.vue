<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ojv7dhbgt"/><path class="q6ks_0b9n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:garden-shed" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ojv7dhbgt {
  d: path("m2.5 9.5l19-4.5m-17 4v12.5h15v-16");
}

.q6ks_0b9n {
  d: path("M9 12h4a1.5 1.5 0 0 1 1.5 1.5V20a1.5 1.5 0 0 1-1.5 1.5H9A1.5 1.5 0 0 1 7.5 20v-6.5A1.5 1.5 0 0 1 9 12m-1.5 2.5h7m-7 4.5h7m-7 0l7-4.5");
}

</style>
