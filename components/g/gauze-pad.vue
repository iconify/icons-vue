<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="hvixtqbcd"/><path class="hmx1jhbgo"/><rect class="h4nbz5b4q"/><rect class="y6whqt0cj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gauze-pad" /></template>
<style>
.h4nbz5b4q {
  width: 5px;
  height: 2.5px;
  x: 2.75px;
  y: 10.75px;
  rx: 0.75px;
}

.hmx1jhbgo {
  d: path("m5.25 10.25l5-5m-5 10l10-10m-6.5 13.5l10-10m-5 10l5-5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hvixtqbcd {
  width: 13.5px;
  height: 13.5px;
  x: 5.25px;
  y: 5.25px;
  rx: 2px;
}

.y6whqt0cj {
  width: 5px;
  height: 2.5px;
  x: 16.25px;
  y: 10.75px;
  rx: 0.75px;
}

</style>
