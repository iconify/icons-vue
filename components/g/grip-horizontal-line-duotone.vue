<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="zo874nbdq"/><circle class="mfdgc7b0x"/><circle class="lekigjbvy"/><circle class="hzbwlrnku"/><circle class="zjx9kz-ib"/><circle class="f3sty6bdo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:grip-horizontal-line-duotone" /></template>
<style>
.f3sty6bdo {
  cx: 19px;
  cy: 8.488px;
  r: 0.75px;
}

.hzbwlrnku {
  cx: 5px;
  cy: 8.504px;
  r: 0.75px;
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lekigjbvy {
  cx: 19px;
  cy: 15.496px;
  r: 0.75px;
}

.mfdgc7b0x {
  cx: 12px;
  cy: 15.512px;
  r: 0.75px;
  opacity: var(--svg-opacity--0-5, 0.5);
}

.zjx9kz-ib {
  cx: 12px;
  cy: 8.504px;
  r: 0.75px;
  opacity: var(--svg-opacity--0-5, 0.5);
}

.zo874nbdq {
  cx: 5px;
  cy: 15.512px;
  r: 0.75px;
}

</style>
