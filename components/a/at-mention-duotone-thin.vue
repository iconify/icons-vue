<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n2xwwpbqf"/><path class="rorj5dbvh"/><path class="cp7471bfa"/><path class="s-ysp2bbt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:at-mention-duotone-thin" /></template>
<style>
.cp7471bfa {
  d: path("M14.5 9v7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n2xwwpbqf {
  fill: currentColor;
  d: path("M7 12.5a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.rorj5dbvh {
  d: path("M7 12.5a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
}

.s-ysp2bbt {
  d: path("M20.16 15.8a9 9 0 1 1 0 -7.6");
}

</style>
