<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="rjrm_epcf"/><circle class="en3_6abys"/><circle class="o__720brd"/><path class="pi82abcxz"/><path class="xnjmplb7c"/><path class="qkx_1mbrk"/><path class="wxv4w3brh"/><ellipse class="wssmm9fxn"/><path class="iggapg5xy"/><path class="kodk3sbyv"/><path class="yykqx9hnh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kitchenowl" /></template>
<style>
.en3_6abys {
  cx: 28.293px;
  cy: 30.878px;
  r: 0.587px;
}

.iggapg5xy {
  d: path("M21.117 34.502c1.009 3.11 3.915 5.188 7.19 5.188c4.069 0 7.407-3.218 7.548-7.278m.008-11.722v11.593m-4.247-9.337a6.15 6.15 0 0 0 4.237-2.499m-4.339 2.505H16.346");
}

.kodk3sbyv {
  d: path("M33.252 43.37c-.083-1.734-.42-3.4-.976-4.833m-6.014-24.461a5.04 5.04 0 0 0 1.881-1.573m.86-1.949q.102-.5.103-1.01a5.04 5.04 0 0 0-4.939-5.037");
}

.o__720brd {
  cx: 19.751px;
  cy: 30.926px;
  r: 3.81px;
}

.pi82abcxz {
  d: path("M21.04 34.738c.867-.784 1.866-1.144 3.01-1.144c1.085 0 2.138.388 2.985 1.1");
}

.qkx_1mbrk {
  d: path("M14.75 43.42c.083-1.74.42-3.41.977-4.848m-.934 4.928h18.403M21.747 14.096a5.05 5.05 0 0 1-1.883-1.577m-.861-1.955a5.05 5.05 0 0 1 5.18-6.059");
}

.rjrm_epcf {
  cx: 19.821px;
  cy: 30.877px;
  r: 0.587px;
}

.wssmm9fxn {
  cx: 28.255px;
  cy: 30.91px;
  rx: 3.807px;
  ry: 3.8px;
}

.wxv4w3brh {
  d: path("M17.809 14.867a5.051 5.051 0 0 1 2.282-9.557c.355 0 .536.019.884.093m-3.144 9.644v5.438m.07.002h8.402");
}

.xnjmplb7c {
  d: path("M26.878 34.542a7.56 7.56 0 0 1-14.733-2.11m-.008-11.754v11.624m4.25-9.362a6.15 6.15 0 0 1-4.24-2.505m4.343 2.511h15.18");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yykqx9hnh {
  d: path("M30.196 14.894a5.04 5.04 0 0 0 2.766-4.494a5.04 5.04 0 0 0-5.046-5.038c-.355 0-.512.038-.86.112m3.118 9.599v5.423m-.07.003H21.71");
}

</style>
