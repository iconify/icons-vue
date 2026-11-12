<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="ucr1abtlg"/><circle class="xi0zi8b-f"/><circle class="rf2iq2_-s"/><circle class="b0x94kb-u"/><circle class="wply1zb2x"/><circle class="ne3znqnan"/><circle class="ofiabdbkw"/><circle class="c0odglb-w"/><circle class="vy0kz1bbg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:grip-broken" /></template>
<style>
.b0x94kb-u {
  cx: 5.008px;
  cy: 19px;
  r: 0.75px;
}

.c0odglb-w {
  cx: 19.008px;
  cy: 12px;
  r: 0.75px;
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ne3znqnan {
  cx: 4.992px;
  cy: 5px;
  r: 0.75px;
}

.ofiabdbkw {
  cx: 19.008px;
  cy: 19px;
  r: 0.75px;
}

.rf2iq2_-s {
  cx: 12px;
  cy: 5px;
  r: 0.75px;
}

.ucr1abtlg {
  cx: 12.016px;
  cy: 19px;
  r: 0.75px;
}

.vy0kz1bbg {
  cx: 18.992px;
  cy: 5px;
  r: 0.75px;
}

.wply1zb2x {
  cx: 5.008px;
  cy: 12px;
  r: 0.75px;
}

.xi0zi8b-f {
  cx: 12.016px;
  cy: 12px;
  r: 0.75px;
}

</style>
