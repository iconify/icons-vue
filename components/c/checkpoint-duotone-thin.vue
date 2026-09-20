<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ja0_o1hya"/><path class="o53lhrb2a"/><path class="ftqzjnb8u"/><path class="qnhyftzmc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:checkpoint-duotone-thin" /></template>
<style>
.ftqzjnb8u {
  d: path("M6 3v18");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ja0_o1hya {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.o53lhrb2a {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 5h12v7H6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qnhyftzmc {
  d: path("M6 5h12v7H6");
}

</style>
