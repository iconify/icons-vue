<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h4w5bebie"/><path class="t0qed8bou"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:express-lane" /></template>
<style>
.h4w5bebie {
  d: path("M13.277 20.5H6.691q-.114 0-.228-.01t-.226-.03q-.113-.019-.223-.049q-.11-.029-.218-.068q-.107-.039-.21-.087q-.104-.048-.203-.105t-.193-.122t-.181-.138t-.169-.154t-.154-.168q-.074-.087-.14-.18t-.123-.192t-.106-.202t-.089-.21q-.039-.107-.069-.218q-.031-.11-.051-.222l-1.045-5.75q-.013-.071-.022-.142t-.014-.143t-.006-.143t.002-.144q.002-.072.009-.143q.007-.072.017-.143t.025-.141t.033-.14q.019-.069.041-.138q.022-.068.047-.135t.056-.133q.029-.065.062-.129t.069-.126t.076-.121t.083-.118t.089-.113t.095-.107t.101-.103q.051-.049.106-.096q.054-.047.111-.091t.116-.085t.121-.078q.061-.037.124-.071q.064-.034.129-.064q.065-.031.131-.058q.067-.027.135-.05t.137-.042t.139-.035t.141-.028t.142-.019q.072-.008.143-.012q.072-.004.144-.004h12.71q.118 0 .235.011t.233.031t.229.053q.114.031.224.072q.11.042.217.093q.106.051.207.111t.196.129q.095.07.184.147t.17.162q.082.086.155.178q.074.091.139.19q.065.098.121.202q.056.103.102.211q.046.109.083.22q.036.112.063.227q.026.115.042.232M7 9.5l3-6m7 6l-3-6m-6.5 9v5m4-5v5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t0qed8bou {
  d: path("m19 13.75l-3.75 4.75l5-.5l-3.5 4");
}

</style>
