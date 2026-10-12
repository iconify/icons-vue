<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="kt8s0oi2f"/><rect class="iinrrlyhq"/><path class="w-amiuzjk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bath-salt" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iinrrlyhq {
  width: 9px;
  height: 12.5px;
  x: 2.75px;
  y: 8.75px;
  rx: 2.5px;
}

.kt8s0oi2f {
  width: 6px;
  height: 3px;
  x: 4.25px;
  y: 2.75px;
  rx: 1px;
}

.w-amiuzjk {
  d: path("m16.52 19.88l-.84.84q-.28.28-.56 0l-.84-.84q-.28-.28 0-.56l.84-.84q.28-.28.56 0l.84.84q.28.28 0 .56m4.45 0l-.84.84q-.28.28-.56 0l-.84-.84q-.28-.28 0-.56l.84-.84q.28-.28.56 0l.84.84q.28.28 0 .56m-2.25-5l-.84.84q-.28.28-.56 0l-.84-.84q-.28-.28 0-.56l.84-.84q.28-.28.56 0l.84.84q.28.28 0 .56");
}

</style>
