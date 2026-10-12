<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hx9xoqbwx"/><rect class="ndfv33b2b"/><path class="iuqyh7mid"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bolt-cutter" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hx9xoqbwx {
  d: path("m12.58 3.22l1.59 1.31q.58.47.4 1.2l-.39 1.54Q14 8 13.25 8h-2.5q-.75 0-.93-.73l-.39-1.54q-.18-.73.4-1.2l1.59-1.31q.58-.47 1.16 0");
}

.iuqyh7mid {
  d: path("M12 5.25V8m-1.25 3.25L7.5 17m5.75-5.75L16.5 17m-9.08-.66l.66.32q.67.34.29.99L6.63 20.6q-.38.65-1.05.31l-.66-.32q-.67-.34-.29-.99l1.74-2.95q.38-.65 1.05-.31m10.21.31l1.74 2.95q.38.65-.29.99l-.66.32q-.67.34-1.05-.31l-1.74-2.95q-.38-.65.29-.99l.66-.32q.67-.34 1.05.31");
}

.ndfv33b2b {
  width: 5px;
  height: 3.5px;
  x: 9.5px;
  y: 7.75px;
  rx: 1.25px;
}

</style>
