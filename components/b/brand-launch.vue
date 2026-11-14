<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rm4evybhx"/><path class="q7zhaibtf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:brand-launch" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q7zhaibtf {
  d: path("M7.086 10.5H5.681a1.5 1.5 0 0 0-1.129.512l-.427.488a.603.603 0 0 0 .454 1h1.3a1.5 1.5 0 0 0 1.06-.439L7.5 11.5a.586.586 0 0 0-.414-1m6.414 6.414v1.405a1.5 1.5 0 0 1-.512 1.129l-.488.427a.603.603 0 0 1-1-.454v-1.3a1.5 1.5 0 0 1 .439-1.06l.561-.561a.586.586 0 0 1 1 .414M13.5 9a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m-6 8.5l-3 3");
}

.rm4evybhx {
  d: path("M6.5 12.5L13 6c2-2 5-2.5 7.5-2.5C20.5 6 20 9 18 11l-6.5 6.5Z");
}

</style>
