<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sit--0bqn"/><path class="ea9l1gvxm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:film-statuette" /></template>
<style>
.ea9l1gvxm {
  d: path("m12.375 6.5l.024.064a1.44 1.44 0 0 0 1.351.936a.414.414 0 0 1 .293.707l-.192.192a1.5 1.5 0 0 0-.395 1.425L13.5 10a.38.38 0 0 1-.589.401l-.039-.028a1.5 1.5 0 0 0-1.744 0l-.039.028A.38.38 0 0 1 10.5 10l.044-.176a1.5 1.5 0 0 0-.395-1.425l-.192-.192a.414.414 0 0 1 .293-.707a1.44 1.44 0 0 0 1.351-.936l.024-.064a.401.401 0 0 1 .75 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sit--0bqn {
  d: path("M5.5 2.5h13V8a6.5 6.5 0 0 1-13 0Zm6.5 12v3m-2.25 0h4.5A1.75 1.75 0 0 1 16 19.25v.5a1.75 1.75 0 0 1-1.75 1.75h-4.5A1.75 1.75 0 0 1 8 19.75v-.5a1.75 1.75 0 0 1 1.75-1.75");
}

</style>
