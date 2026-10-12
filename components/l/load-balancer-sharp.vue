<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="e9-7-8-2z"/><path class="sn3pd3b2c"/><circle class="fxwnb7vgp"/><circle class="zopjch_2q"/><circle class="xtsrmvj7o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:load-balancer-sharp" /></template>
<style>
.e9-7-8-2z {
  cx: 12px;
  cy: 4.75px;
  r: 2px;
}

.fxwnb7vgp {
  cx: 5px;
  cy: 19px;
  r: 2px;
}

.sn3pd3b2c {
  d: path("M12 6.75V12m-7 5v-5h14v5m-7-5v5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xtsrmvj7o {
  cx: 19px;
  cy: 19px;
  r: 2px;
}

.zopjch_2q {
  cx: 12px;
  cy: 19px;
  r: 2px;
}

</style>
