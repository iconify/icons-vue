<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qrrk34pyq"/><path class="si2woy-1u"/><path class="di7hdqbmq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:donor-database" /></template>
<style>
.di7hdqbmq {
  d: path("M3 10.75q0 .061.008.123q.008.061.025.122q.016.061.04.122t.057.121t.072.119q.041.06.089.119t.104.116t.119.115q.063.056.134.112q.071.055.149.109q.078.055.163.107q.086.053.178.104t.19.1t.204.097t.217.093t.228.089t.24.084q.123.042.251.081q.128.038.261.075t.271.071t.28.065q.142.032.288.061t.296.055t.303.05q.153.023.309.044t.315.038t.319.033t.323.027q.163.012.327.021q.163.009.328.015t.331.009q.165.003.331.003q.633 0 1.255-.044q.622-.043 1.211-.129q.589-.085 1.125-.21t1-.284m.159 8.667c0-1.5 1.5-2.5 3.5-2.5s3.5 1 3.5 2.5c0 .25-.25.5-.5.5h-6c-.25 0-.5-.25-.5-.5Zm1.75-6a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

.qrrk34pyq {
  d: path("M3 5a6.75 2.5 0 1 0 13.5 0A6.75 2.5 0 1 0 3 5Z");
}

.si2woy-1u {
  d: path("M3 5v12.5q0 .061.008.123q.008.061.025.122q.016.061.04.122t.057.121t.072.119q.041.06.089.119t.104.116q.055.058.119.115q.063.056.134.112q.071.055.149.109q.078.055.163.107q.086.053.178.104t.19.1t.204.097t.217.093t.228.089t.24.084q.123.042.251.081q.128.038.261.075t.271.071t.28.065q.142.032.288.061t.296.055t.303.05t.309.044t.315.038t.319.033t.323.027t.327.021t.328.015t.331.009q.165.003.331.003q1.114 0 2.17-.133m4.58-8.888V5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
