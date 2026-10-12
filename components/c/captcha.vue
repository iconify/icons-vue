<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="t0fnjfb_f"/><rect class="e3llb48zn"/><rect class="ysa-7fika"/><rect class="p8n9i911v"/><path class="ni6nfmb8z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:captcha" /></template>
<style>
.e3llb48zn {
  width: 7.75px;
  height: 7.75px;
  x: 13.5px;
  y: 2.75px;
  rx: 1.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ni6nfmb8z {
  d: path("m15.5 6.75l1.5 1.5l2.5-2.75m-14.75 12l1.5 1.5l2.5-2.75");
}

.p8n9i911v {
  width: 7.75px;
  height: 7.75px;
  x: 13.5px;
  y: 13.5px;
  rx: 1.5px;
}

.t0fnjfb_f {
  width: 7.75px;
  height: 7.75px;
  x: 2.75px;
  y: 2.75px;
  rx: 1.5px;
}

.ysa-7fika {
  width: 7.75px;
  height: 7.75px;
  x: 2.75px;
  y: 13.5px;
  rx: 1.5px;
}

</style>
