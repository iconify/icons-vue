<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k6cb4absm"/><path class="bq549vbki"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:brush-cutter" /></template>
<style>
.bq549vbki {
  d: path("M14 8.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m.5 1l-6.75 6.75M3.379 18.5L5.5 16.379a1.5 1.5 0 0 1 2.121 0a1.5 1.5 0 0 1 0 2.121L5.5 20.621a1.5 1.5 0 0 1-2.121 0a1.5 1.5 0 0 1 0-2.121");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k6cb4absm {
  d: path("M20 10.375za.377.377 0 0 1-.029.686l-2.192.878A.77.77 0 0 0 17.375 13a.319.319 0 0 1-.404.439l-2.192-.878a.91.91 0 0 0-1.154.439a.377.377 0 0 1-.686-.029l-.878-2.192A.77.77 0 0 0 11 10.375a.319.319 0 0 1-.439-.404l.878-2.192A.91.91 0 0 0 11 6.625a.377.377 0 0 1 .029-.686l2.192-.878A.77.77 0 0 0 13.625 4a.319.319 0 0 1 .404-.439l2.192.878A.91.91 0 0 0 17.375 4a.377.377 0 0 1 .686.029l.878 2.192A.77.77 0 0 0 20 6.625a.319.319 0 0 1 .439.404l-.878 2.192A.91.91 0 0 0 20 10.375");
}

</style>
