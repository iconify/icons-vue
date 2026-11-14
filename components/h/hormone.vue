<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ja50hac2k"/><path class="lz7y7c-ck"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hormone" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ja50hac2k {
  d: path("m9 9.933l2.397 1.384a1.5 1.5 0 0 1 .75 1.299v2.768a1.5 1.5 0 0 1-.75 1.299L9 18.067a1.5 1.5 0 0 1-1.5 0l-2.397-1.384a1.5 1.5 0 0 1-.75-1.299v-2.768a1.5 1.5 0 0 1 .75-1.299L7.5 9.933a1.5 1.5 0 0 1 1.5 0");
}

.lz7y7c-ck {
  d: path("m16.75 9.933l2.397 1.384a1.5 1.5 0 0 1 .75 1.299v2.768a1.5 1.5 0 0 1-.75 1.299l-2.397 1.384a1.5 1.5 0 0 1-1.5 0l-2.397-1.384a1.5 1.5 0 0 1-.75-1.299v-2.768a1.5 1.5 0 0 1 .75-1.299l2.397-1.384a1.5 1.5 0 0 1 1.5 0M16 9.5v-3l3-2");
}

</style>
