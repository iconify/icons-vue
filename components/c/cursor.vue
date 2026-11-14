<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l45dodb_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cursor" /></template>
<style>
.l45dodb_q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 6.41v9.849a1.188 1.188 0 0 0 2 .866l.447-.419a1.5 1.5 0 0 1 2.402.496l1.049 2.413a1.486 1.486 0 0 0 1.977.76l.032-.014a1.5 1.5 0 0 0 .755-1.964l-1-2.299A1.5 1.5 0 0 1 15.538 14h.337a1.021 1.021 0 0 0 .69-1.774L9.014 5.304A1.5 1.5 0 0 0 6.5 6.41");
}

</style>
