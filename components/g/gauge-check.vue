<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tboaly66y"/><path class="c5nup6bhu"/><path class="s7v73ac1b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gauge-check" /></template>
<style>
.c5nup6bhu {
  fill: currentColor;
  d: path("M10.75 14a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s7v73ac1b {
  d: path("m14.5 18l2.5 2.5l4.5-5");
}

.tboaly66y {
  d: path("M3 14q0-.221.011-.442q.011-.22.033-.44q.021-.22.054-.438q.032-.219.075-.435q.044-.217.097-.431q.054-.215.118-.426t.139-.419q.074-.208.159-.412t.179-.404t.199-.394q.104-.195.217-.385q.114-.189.237-.373q.123-.183.254-.361q.132-.177.272-.348t.289-.334q.148-.164.304-.32t.32-.304q.164-.149.335-.289q.17-.14.348-.272q.177-.131.361-.254q.184-.122.373-.236t.384-.218t.395-.198t.404-.179t.412-.159t.419-.139q.211-.064.426-.117q.214-.054.431-.097q.216-.043.435-.076q.218-.032.438-.054t.44-.032q.221-.011.442-.011q.201 0 .403.009q.201.009.401.027q.201.018.401.045q.199.027.397.063q.199.036.395.08t.391.099q.194.053.385.115q.192.062.381.133q.188.07.373.149q.186.079.367.166q.182.087.359.183q.178.095.351.198t.341.214t.332.228t.321.244q.157.125.309.257t.298.271t.286.284q.139.146.272.297t.259.308t.245.32q.118.163.23.33q.111.168.215.341q.104.172.2.349q.096.178.184.359t.168.366t.151.373t.134.38q.063.191.118.385t.099.39q.046.196.083.394t.064.398M3 14h2m7 0V7.5");
}

</style>
