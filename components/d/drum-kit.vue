<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a7dn90b8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:drum-kit" /></template>
<style>
.a7dn90b8g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14.5a6 6 0 1 0 12 0a6 6 0 1 0-12 0M5.792 4.021l3.381-.906a1.75 1.75 0 0 1 2.143 1.238l.065.241a1.75 1.75 0 0 1-1.238 2.143l-3.38.906a1.75 1.75 0 0 1-2.144-1.237l-.064-.242a1.75 1.75 0 0 1 1.237-2.143M14.75 5.25c1-2 5.5-2 6.5 0Zm3.25 0V18m-2 2.5l2-2.5l2 2.5");
}

</style>
