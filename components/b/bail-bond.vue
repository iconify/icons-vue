<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="xahckxbvj"/><path class="rtoy__b5z"/><rect class="mybs6-bik"/><path class="q02-ao_6j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bail-bond" /></template>
<style>
.mybs6-bik {
  width: 6.5px;
  height: 5.5px;
  x: 14.75px;
  y: 15.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

.q02-ao_6j {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18 18.5h.01");
}

.rtoy__b5z {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 8.75c-.5-.75-1.25-1-2-1c-1.25 0-2 .6-2 1.5c0 2 4 1 4 3c0 .9-.75 1.5-2 1.5c-.75 0-1.5-.25-2-1m2-6.5v1.5m0 6v1.5m8.25.5V15a2 2 0 0 1 4 0v.75");
}

.xahckxbvj {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 2.75h9a2 2 0 0 1 2 2V11h-2.5a1 1 0 0 0-1 1v9.25h-7.5a2 2 0 0 1-2-2V4.75a2 2 0 0 1 2-2");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
