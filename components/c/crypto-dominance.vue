<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i39cgdbzp"/><path class="ss_pw809k"/><path class="nr2kwkbiv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:crypto-dominance" /></template>
<style>
.i39cgdbzp {
  d: path("M14.245 12.75H9.75V5.5q-.178 0-.356.009t-.355.026t-.353.043t-.35.061t-.348.078q-.172.044-.343.095q-.17.052-.337.112q-.168.06-.332.128q-.165.068-.326.144t-.318.16t-.309.175t-.301.191t-.291.205t-.28.219t-.27.232t-.258.245t-.245.258q-.119.132-.232.27q-.113.137-.219.28t-.205.291t-.191.301t-.175.309t-.16.318t-.144.326t-.128.332t-.112.337q-.051.171-.095.343q-.043.173-.078.348q-.034.174-.061.35t-.043.353q-.018.177-.026.355t-.009.356t.009.356q.008.178.026.355t.043.353q.027.176.061.35q.035.175.078.348q.044.172.095.343q.052.17.112.337q.06.168.128.332q.068.165.144.326t.16.318t.175.309t.191.301t.205.291t.219.28t.232.27q.12.132.245.258q.126.125.258.245q.132.119.27.232q.137.113.28.219t.291.205t.301.191q.152.091.309.175t.318.16t.326.144t.332.128t.337.112q.171.051.343.095q.173.043.348.078q.174.034.35.061t.353.043q.177.018.355.026T9.75 20q.877 0 1.729-.209");
}

.nr2kwkbiv {
  d: path("M17 15h2a3 3 0 0 1 0 6h-2");
}

.ss_pw809k {
  d: path("M12.5 10V2.75A7.25 7.25 0 0 1 19.75 10Zm1.5 8a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
