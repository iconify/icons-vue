<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eosu34bne"/><path class="duwpa-lxo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:convenience-store" /></template>
<style>
.duwpa-lxo {
  d: path("M8.25 11.25h7.5A1.25 1.25 0 0 1 17 12.5a1.25 1.25 0 0 1-1.25 1.25h-7.5A1.25 1.25 0 0 1 7 12.5a1.25 1.25 0 0 1 1.25-1.25M8.5 17h7");
}

.eosu34bne {
  d: path("M3 6.5L4.5 3h15L21 6.5m-18 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0M9.721 13.75h4.558a1.5 1.5 0 0 1 1.486 1.705l-.586 4.25A1.5 1.5 0 0 1 13.693 21h-3.386a1.5 1.5 0 0 1-1.486-1.295l-.586-4.25a1.5 1.5 0 0 1 1.486-1.705");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
