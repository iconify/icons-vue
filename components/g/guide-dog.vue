<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cce0qkb-c"/><rect class="qqxymhb_c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:guide-dog" /></template>
<style>
.cce0qkb-c {
  d: path("M5.35 11h8.8q.6 0 .75-.58l.95-3.84q.15-.58.57-1l.66-.66q.42-.42.89-.05l.31.26q.47.37 1.01.64l1.42.71q.54.27.44.86l-.05.32q-.1.59-.7.65l-1.3.13q-.6.06-.71.65l-.53 2.82q-.11.59-.11 1.19v7.55q0 .6-.6.6h-.55q-.6 0-.71-.59l-.78-4.32q-.11-.59-.71-.59H9.6q-.6 0-.76.58l-1.18 4.34q-.16.58-.76.58h-.55q-.6 0-.6-.6V15.6q0-.6-.15-1.18l-.7-2.84q-.15-.58.45-.58m-.6.25l-2-2.75M8.5 11l1.75-5.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qqxymhb_c {
  width: 5px;
  height: 2.5px;
  x: 9.25px;
  y: 3px;
  rx: 1.25px;
}

</style>
