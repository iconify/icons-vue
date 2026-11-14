<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fuhvvghst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:airport-beacon" /></template>
<style>
.fuhvvghst {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 5.5zA2.5 2.5 0 0 1 14.5 8v1a2.5 2.5 0 0 1-2.5 2.5A2.5 2.5 0 0 1 9.5 9V8A2.5 2.5 0 0 1 12 5.5m0 6v8m-3.5 0h7M6.549 7.138l-1.42-.656A1.5 1.5 0 0 0 3 7.844v1.312a1.5 1.5 0 0 0 2.129 1.362l1.42-.656a1.5 1.5 0 0 0 0-2.724m10.902 0l1.42-.656A1.5 1.5 0 0 1 21 7.844v1.312a1.5 1.5 0 0 1-2.129 1.362l-1.42-.656a1.5 1.5 0 0 1 0-2.724");
}

</style>
