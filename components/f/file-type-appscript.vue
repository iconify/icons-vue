<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="h_vnju28d"/><circle class="n7jn0-www"/><rect transform="rotate(-144 239.832 304.447)" class="f-ryfab9x"/><circle class="b6cjfxbju"/><rect transform="rotate(72 307.032 255.396)" class="esmzz6hat"/><circle class="m78o3mgot"/><rect transform="rotate(-72 389.029 255.392)" class="btmnjfrxg"/><circle class="sstj0fbso"/><circle class="e5d7emcjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-appscript" /></template>
<style>
.b6cjfxbju {
  cx: 131.44px;
  cy: 225.44px;
  r: 26.7px;
  fill: var(--svg-color--fff, #fff);
}

.btmnjfrxg {
  width: 373px;
  height: 107px;
  x: 202.53px;
  y: 201.9px;
  fill: var(--svg-color--4285f4, #4285f4);
  rx: 53.5px;
}

.e5d7emcjv {
  cx: 430.67px;
  cy: 127.89px;
  r: 26.7px;
  fill: var(--svg-color--fff, #fff);
}

.esmzz6hat {
  width: 373px;
  height: 107px;
  x: 120.53px;
  y: 201.9px;
  fill: var(--svg-color--34a853, #34a853);
  rx: 53.5px;
}

.f-ryfab9x {
  width: 373px;
  height: 107px;
  x: 53.33px;
  y: 250.94px;
  fill: var(--svg-color--fbbc04, #fbbc04);
  rx: 53.5px;
}

.h_vnju28d {
  width: 373px;
  height: 107px;
  x: 27.53px;
  y: 328.9px;
  fill: var(--svg-color--ea4335, #ea4335);
  rx: 53.5px;
}

.m78o3mgot {
  cx: 265.84px;
  cy: 129.28px;
  r: 26.7px;
  fill: var(--svg-color--fff, #fff);
}

.n7jn0-www {
  cx: 81.36px;
  cy: 382.6px;
  r: 26.7px;
  fill: var(--svg-color--fff, #fff);
}

.sstj0fbso {
  cx: 348.22px;
  cy: 381.64px;
  r: 26.7px;
  fill: var(--svg-color--fff, #fff);
}

</style>
