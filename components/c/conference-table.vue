<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="b-kibvb9r"/><rect class="a4du-rxjj"/><rect class="vj_xevbii"/><rect class="v6m71_bsb"/><rect class="g8k05sbgb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:conference-table" /></template>
<style>
.a4du-rxjj {
  width: 3px;
  height: 3.5px;
  x: 2.75px;
  y: 6.5px;
  rx: 1px;
}

.b-kibvb9r {
  width: 6.5px;
  height: 16.5px;
  x: 8.75px;
  y: 3.75px;
  rx: 3.25px;
}

.g8k05sbgb {
  width: 3px;
  height: 3.5px;
  x: 18.25px;
  y: 14px;
  rx: 1px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v6m71_bsb {
  width: 3px;
  height: 3.5px;
  x: 18.25px;
  y: 6.5px;
  rx: 1px;
}

.vj_xevbii {
  width: 3px;
  height: 3.5px;
  x: 2.75px;
  y: 14px;
  rx: 1px;
}

</style>
