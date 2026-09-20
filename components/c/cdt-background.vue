<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ighbb7b2g"/><path class="c_1l24mde"/><path class="zba36qbvi"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cdt-background" /></template>
<style>
.c_1l24mde {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.714 7.36c-.288.14-.53.361-.693.636L12 12.057v7.93c.209.04.329-.014.378-.045c1.885-1.093 5.765-3.334 6.197-3.556a1.04 1.04 0 0 0 .538-.92v-2.37l-1.334.796v1.094c0 .289-.156.444-.231.48l-3.792 2.196c-.387.218-.418.022-.422-.103v-6.29c-1.712-1-5.273-3.031-5.504-3.17c-.235-.137-.098-.333 0-.413l3.85-2.231c.222-.174.462-.067.578 0l1 .587l1.29-.76a135 135 0 0 0-1.992-1.143a1.29 1.29 0 0 0-1.16 0C9.68 5.12 6.136 7.143 5.714 7.36");
}

.ft5dv1b6b {
  fill: none;
}

.ighbb7b2g {
  fill: var(--svg-color--047fff, #047fff);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.zba36qbvi {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.887 15.438V8.681l1.334.734c.009 1.658.022 5.067 0 5.467s.178.632.329.703l4.756 2.756v1.462l-5.547-3.21c-.774-.461-.89-.888-.867-1.155zm13.505-7.944l-3.134-1.827l-1.315.756a64 64 0 0 1 3.391 2c.37.28.445.738.445.93v3.774l1.334-.774c-.005-.925-.014-2.943 0-3.632a1.38 1.38 0 0 0-.72-1.227");
}

</style>
