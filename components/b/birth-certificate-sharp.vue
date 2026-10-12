<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="bh4biibbp"/><circle class="zt548wbiy"/><path class="rrzohjbez"/><circle class="bopak3bua"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:birth-certificate-sharp" /></template>
<style>
.bh4biibbp {
  d: path("M4.75 2.75h14.5v18.5H4.75z");
}

.bopak3bua {
  cx: 12px;
  cy: 16.75px;
  r: 1.75px;
}

.rrzohjbez {
  d: path("M12 12v3");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zt548wbiy {
  cx: 12px;
  cy: 8.75px;
  r: 3.25px;
}

</style>
