<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="ns6fdjbuv"/><ellipse transform="rotate(-45 31.956 16.044)" class="uwdvqnbax"/><ellipse class="em6x8hrzf"/><ellipse transform="rotate(-45 31.956 31.956)" class="a2gjjfblb"/><ellipse class="ikafwwb3r"/><ellipse transform="rotate(-45 16.044 31.956)" class="qkt-117wi"/><ellipse class="q003fdcoh"/><ellipse transform="rotate(-45 16.044 16.044)" class="oszc9cb1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gallery-alt-1" /></template>
<style>
.a2gjjfblb {
  cx: 31.956px;
  cy: 31.956px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.558px;
  ry: 10.248px;
}

.em6x8hrzf {
  cx: 35.252px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 10.248px;
  ry: 5.558px;
}

.ikafwwb3r {
  cx: 24px;
  cy: 35.252px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.558px;
  ry: 10.248px;
}

.ns6fdjbuv {
  cx: 24px;
  cy: 12.748px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.558px;
  ry: 10.248px;
}

.oszc9cb1x {
  cx: 16.044px;
  cy: 16.044px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.558px;
  ry: 10.248px;
}

.q003fdcoh {
  cx: 12.748px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 10.248px;
  ry: 5.558px;
}

.qkt-117wi {
  cx: 16.044px;
  cy: 31.956px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 10.248px;
  ry: 5.558px;
}

.uwdvqnbax {
  cx: 31.956px;
  cy: 16.044px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 10.248px;
  ry: 5.558px;
}

</style>
