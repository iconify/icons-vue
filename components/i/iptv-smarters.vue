<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="imcxvgbdh"/><circle class="vnl304pwq"/><circle class="zh-t3dbfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:iptv-smarters" /></template>
<style>
.imcxvgbdh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.105 42.5c2.499-.401 6.885-.041 8.66-5.295m-.193-18.746c-.873-2.128-2.52-2.998-5.612-3.176c-5.582-.321-18.31 1.47-22.956 2.83c-3.271.958-3.274 4.903-3.274 4.903m4.13.227l.597 11.568m3.223-.173l-.598-11.568l3.718-.2a3.91 3.91 0 0 1 .403 7.809l-3.718.2m10.4-8.389l7.579-.407m-3.121 11.768l-.598-11.568m14.525-.778l-3.121 11.768l-4.459-11.361M20.34 16.04l-4.682-8.064m6.452 7.796l1.819-7.41");
}

.vnl304pwq {
  cx: 15.015px;
  cy: 6.822px;
  r: 1.322px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zh-t3dbfy {
  cx: 24.343px;
  cy: 7.106px;
  r: 1.322px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
