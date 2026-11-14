<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b5kbv67xa"/><path class="u-l716quj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:city-view" /></template>
<style>
.b5kbv67xa {
  d: path("M6.625 3h10.75A2.625 2.625 0 0 1 20 5.625v11.25a2.625 2.625 0 0 1-2.625 2.625H6.625A2.625 2.625 0 0 1 4 16.875V5.625A2.625 2.625 0 0 1 6.625 3M2.5 19.5h19");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u-l716quj {
  d: path("M8 11.5zA1.5 1.5 0 0 1 9.5 13v5A1.5 1.5 0 0 1 8 19.5A1.5 1.5 0 0 1 6.5 18v-5A1.5 1.5 0 0 1 8 11.5m2.75 6.5V8.915a1.5 1.5 0 0 1 .214-.771l.536-.894a.875.875 0 0 1 1.5 0l.536.894a1.5 1.5 0 0 1 .214.771V18a1.5 1.5 0 0 1-1.5 1.5a1.5 1.5 0 0 1-1.5-1.5m5.5-8.5za1.25 1.25 0 0 1 1.25 1.25v7.5a1.25 1.25 0 0 1-1.25 1.25A1.25 1.25 0 0 1 15 18.25v-7.5a1.25 1.25 0 0 1 1.25-1.25");
}

</style>
