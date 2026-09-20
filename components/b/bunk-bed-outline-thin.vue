<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oti3l4bvo"/><path class="ozi-k-boi"/><path class="hdk8dzk2v"/><path class="ic_pehd5a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bunk-bed-outline-thin" /></template>
<style>
.hdk8dzk2v {
  d: path("M3 21v-7h18v7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ic_pehd5a {
  d: path("M3 17h18");
}

.oti3l4bvo {
  d: path("M3 11V4h18v7");
}

.ozi-k-boi {
  d: path("M3 7h18");
}

</style>
