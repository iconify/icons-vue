<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mqtixbwqo"/><path class="yam3-1b2z"/><path class="mei2sobow"/><path class="xmopbdc-t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:coffee-table-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mei2sobow {
  d: path("M19 8v12");
}

.mqtixbwqo {
  d: path("M2 8h20");
}

.xmopbdc-t {
  d: path("M5 15h14");
}

.yam3-1b2z {
  d: path("M5 8v12");
}

</style>
