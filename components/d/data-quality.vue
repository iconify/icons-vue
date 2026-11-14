<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lmbo0oiji"/><path class="tfl7_hb5z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:data-quality" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lmbo0oiji {
  fill: currentColor;
  d: path("M3 9V6a2.5 2.5 0 0 1 2.5-2.5h13A2.5 2.5 0 0 1 21 6v3Z");
}

.tfl7_hb5z {
  d: path("M3 9v9q0 .123.012.245t.036.243t.06.238t.082.231q.047.113.105.221q.058.109.126.211q.069.102.146.197q.078.095.165.182t.182.165t.197.146t.211.126q.108.058.221.105q.114.047.231.082t.238.06t.243.036t.245.012h7.773M21 12.054V9M3 14.75h9.9M10 9v11.5m8.478-6.28l.046.045a1.5 1.5 0 0 0 1.039.431h.064a.68.68 0 0 1 .677.677v.064a1.5 1.5 0 0 0 .431 1.039l.045.046a.68.68 0 0 1 0 .956l-.045.046a1.5 1.5 0 0 0-.431 1.039v.064a.68.68 0 0 1-.677.677h-.064a1.5 1.5 0 0 0-1.039.431l-.046.045a.68.68 0 0 1-.956 0l-.046-.045a1.5 1.5 0 0 0-1.039-.431h-.064a.68.68 0 0 1-.677-.677v-.064a1.5 1.5 0 0 0-.431-1.039l-.045-.046a.68.68 0 0 1 0-.956l.045-.046a1.5 1.5 0 0 0 .431-1.039v-.064a.68.68 0 0 1 .677-.677h.064a1.5 1.5 0 0 0 1.039-.431l.046-.045a.68.68 0 0 1 .956 0M16.5 19.75L15.75 22m3.75-2.25l.75 2.25");
}

</style>
