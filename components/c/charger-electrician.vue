<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vbrs0hbxf"/><path class="fdoapz1xy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:charger-electrician" /></template>
<style>
.fdoapz1xy {
  d: path("M8.75 5.5L6.5 9h3l-2.25 3.5M21.5 16a2.25 2.25 0 1 1-1.5-1.5M18 18l-3 3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vbrs0hbxf {
  d: path("M3.5 2.5h9v13h-9Zm4.5 13v3q0 .123.012.245t.036.243t.06.238q.035.117.082.231q.047.113.105.221q.058.109.126.211q.069.102.146.197q.078.095.165.182t.182.165t.197.146t.211.126t.221.105q.114.047.231.082t.238.06t.243.036t.245.012h.573");
}

</style>
