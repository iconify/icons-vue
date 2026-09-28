<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGaD8JHd6o" x1="18.871" x2="1.282" y1="16.576" y2="20.932" gradientUnits="userSpaceOnUse"><stop offset="0" class="vdcas_4lg"/><stop offset=".5" class="h0kq64bev"/><stop offset="1" class="mml205bfu"/></linearGradient></defs><path fill="url(#SVGaD8JHd6o)" class="ipe2zkq0u"/><path class="l5jz4mbgn"/><path class="cl_g38vdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-affectscript" /></template>
<style>
.cl_g38vdi {
  fill: var(--svg-color--774eff, #774eff);
  d: path("m26.889 13.1l-1.53 2.65h-9.36l-1.53-2.65z");
}

.h0kq64bev {
  stop-color: var(--svg-color--a04fff, #a04fff);
}

.ipe2zkq0u {
  fill-rule: evenodd;
  d: path("M11.333 7.666L2 23.831h18.667Zm0 5.3l4.745 8.218h-9.49Z");
}

.l5jz4mbgn {
  fill: var(--svg-color--824cff, #824cff);
  d: path("M28.47 10.316L30 7.666H11.333l1.531 2.65z");
}

.mml205bfu {
  stop-color: var(--svg-color--f152ff, #f152ff);
}

.vdcas_4lg {
  stop-color: var(--svg-color--5054ff, #5054ff);
}

</style>
