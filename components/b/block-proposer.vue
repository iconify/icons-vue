<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e_5yewbik"/><path class="zblzeub6w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:block-proposer" /></template>
<style>
.e_5yewbik {
  d: path("m4.1 9.56l9-3.6a1.75 1.75 0 0 1 2.4 1.625v8.83a1.75 1.75 0 0 1-2.4 1.625l-9-3.6A1.75 1.75 0 0 1 3 12.815v-1.63A1.75 1.75 0 0 1 4.1 9.56");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zblzeub6w {
  d: path("M7 15.5V20h3v-3.25M18.5 10L21 8.5M18.5 14l2.5 1.5");
}

</style>
