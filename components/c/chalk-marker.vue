<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pyv255b4a"/><path class="w2pp-sbbo"/><path class="l8j1m1bqt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chalk-marker" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l8j1m1bqt {
  d: path("m15.094 6.255l.446-.149a1.5 1.5 0 0 1 1.535.362l.457.457a1.5 1.5 0 0 1 .362 1.535l-.149.446a.864.864 0 0 1-1.43.338l-1.559-1.559a.864.864 0 0 1 .338-1.43m2.209.442l1.768-1.768");
}

.pyv255b4a {
  d: path("m4.045 15.712l1.061-1.06a1.75 1.75 0 0 1 2.475 0l1.767 1.767a1.75 1.75 0 0 1 0 2.475l-1.06 1.061a1.75 1.75 0 0 1-2.475 0l-1.768-1.768a1.75 1.75 0 0 1 0-2.475");
}

.w2pp-sbbo {
  d: path("m7.757 12.707l4.95-4.95a1.5 1.5 0 0 1 2.121 0l1.415 1.415a1.5 1.5 0 0 1 0 2.121l-4.95 4.95a1.5 1.5 0 0 1-2.121 0l-1.415-1.415a1.5 1.5 0 0 1 0-2.121");
}

</style>
