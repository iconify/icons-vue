<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tr_6_4bqp"/><path class="uo2jyzbgk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:badge-first-win" /></template>
<style>
.tr_6_4bqp {
  d: path("m12 2l1.553 1.204l1.947-.266l.743 1.819l1.819.743l-.266 1.947L19 9l-1.204 1.553l.266 1.947l-1.819.743l-.743 1.819l-1.947-.266L12 16l-1.553-1.204l-1.947.266l-.743-1.819l-1.819-.743l.266-1.947L5 9l1.204-1.553L5.938 5.5l1.819-.743l.743-1.819l1.947.266Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uo2jyzbgk {
  d: path("M8.5 14L7 21l5-2.5l5 2.5l-1.5-7M9 9a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

</style>
