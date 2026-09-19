<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="p1um_wbqu"/><path class="uc0h9s95z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fossilhybrid" /></template>
<style>
.p1um_wbqu {
  width: 37px;
  height: 37px;
  x: 5.501px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.uc0h9s95z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.327 20.297v7.414h3.707m-5.675-7.414v7.414M8.703 20.297h3.706m-3.706 3.707h2.409m-2.409-3.707v7.414m11.406-.812c.454.591 1.024.812 1.817.812h1.098c1.021 0 1.85-.83 1.85-1.853h0a1.85 1.85 0 0 0-1.85-1.854h-1.213c-1.02 0-1.849-.83-1.849-1.853h0a1.85 1.85 0 0 1 1.85-1.853h1.097c.793 0 1.363.22 1.818.812m1.903 5.789c.455.591 1.025.812 1.818.812h1.098c1.021 0 1.85-.83 1.85-1.853h0a1.85 1.85 0 0 0-1.85-1.854h-1.213c-1.021 0-1.85-.83-1.85-1.853h0c0-1.024.829-1.853 1.85-1.853h1.098c.793 0 1.363.22 1.817.812m-17.792 4.137a2.456 2.456 0 1 0 4.911 0v-2.502a2.456 2.456 0 1 0-4.911 0z");
}

</style>
