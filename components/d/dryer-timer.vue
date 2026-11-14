<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sd7or7b7f"/><path class="n2p3zwb2y"/><path class="a6k62accz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dryer-timer" /></template>
<style>
.a6k62accz {
  d: path("M18 16.5V18l1.25 1");
}

.n2p3zwb2y {
  d: path("M15.796 12.34q-.132-.263-.299-.505t-.365-.458t-.426-.404q-.226-.187-.476-.341t-.519-.273t-.552-.198t-.574-.121Q12.294 10 12 10q-.104 0-.209.005q-.104.005-.208.015q-.103.011-.207.026q-.103.015-.205.036t-.204.045q-.101.026-.201.056t-.198.065t-.194.076q-.097.039-.191.084t-.186.094t-.182.103q-.089.053-.176.111t-.171.12t-.164.129t-.158.136t-.151.144t-.144.151t-.136.158q-.066.08-.129.164q-.062.084-.12.171t-.111.176t-.103.182t-.094.186t-.084.191q-.04.096-.076.194t-.065.198q-.03.1-.056.201q-.025.102-.045.204q-.021.102-.036.205q-.015.104-.026.207q-.01.104-.015.208q-.005.105-.005.209t.005.208t.015.208q.011.104.026.207t.036.205t.045.204t.056.201q.03.1.065.198t.075.194t.084.191t.094.186t.103.181t.111.177q.058.086.12.17t.128.164q.066.081.136.158q.07.078.144.151q.074.074.151.144t.158.136t.164.129t.17.12t.176.112q.09.053.181.102q.092.05.187.094q.094.045.19.085t.194.075t.198.066t.201.056t.203.045q.103.021.206.036q.103.016.207.026q.103.01.207.016q.105.005.209.005m2.755-.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

.sd7or7b7f {
  d: path("M13.1 21.5H4.5v-19h15v9.6M4.5 7h15");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
