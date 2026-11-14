<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kebju1mox"/><path class="kiqc7vktt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fire-blanket-sign" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kebju1mox {
  d: path("M7.375 3h9.25A4.375 4.375 0 0 1 21 7.375v9.25A4.375 4.375 0 0 1 16.625 21h-9.25A4.375 4.375 0 0 1 3 16.625v-9.25A4.375 4.375 0 0 1 7.375 3");
}

.kiqc7vktt {
  d: path("M6.5 5.5h11v1.75L15 9.75H6.5ZM15 9.75v-2.5h2.5m-5.5 11c-2.25 0-3.25-1.5-3.25-2.75s1.25-2 2-3c1 .75 1.25 1.5 1 2.25q1.5-.75 1.5-2.25c1.25 1 2 2 2 3.25c0 1.5-1 2.5-3.25 2.5");
}

</style>
