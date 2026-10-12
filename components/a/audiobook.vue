<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uphf8ed4l"/><path class="dck3n9b_z"/><rect class="vhzq2lbad"/><rect class="ed72cz9he"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:audiobook" /></template>
<style>
.dck3n9b_z {
  d: path("M4.13 12.25v-1a7.87 7.87 0 0 1 15.74 0v1");
}

.ed72cz9he {
  width: 2.75px;
  height: 6.5px;
  x: 18.5px;
  y: 12.25px;
  rx: 1.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uphf8ed4l {
  d: path("M12 12.75c-1.1-.9-2.3-1.25-3.5-1.25v8.25c1.2 0 2.4.35 3.5 1.25c1.1-.9 2.3-1.25 3.5-1.25V11.5c-1.2 0-2.4.35-3.5 1.25m0 0V21");
}

.vhzq2lbad {
  width: 2.75px;
  height: 6.5px;
  x: 2.75px;
  y: 12.25px;
  rx: 1.25px;
}

</style>
