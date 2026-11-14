<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n9t4bg3mj"/><path class="cusavpbsj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:geocode" /></template>
<style>
.cusavpbsj {
  d: path("M9.25 9.75a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0m6 7.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m4 1.75L21 21");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n9t4bg3mj {
  d: path("M13.226 20.264c-.422.432-.834.844-1.226 1.236c-3-3-7.25-7.25-7.25-11.75q0-.178.009-.356t.026-.355t.043-.353t.061-.35t.078-.348q.044-.172.095-.343q.052-.17.112-.337q.06-.168.128-.332q.068-.165.144-.326t.16-.318t.175-.309t.191-.301t.205-.291t.219-.28t.232-.27t.245-.258t.258-.245t.27-.232q.137-.113.28-.219t.291-.205t.301-.191t.309-.175t.318-.16t.326-.144t.332-.128t.337-.112q.171-.051.343-.095q.173-.043.348-.078q.174-.034.35-.061t.353-.043q.177-.018.355-.026T12 2.5t.356.009q.178.008.355.026t.353.043q.176.027.35.061q.175.035.348.078q.172.044.343.095q.17.052.337.112q.168.06.332.128q.165.068.326.144t.318.16t.309.175t.301.191t.291.205t.28.219t.27.232q.132.12.258.245q.125.126.245.258q.119.132.232.27q.113.137.219.28t.205.291t.191.301q.091.152.175.309t.16.318t.144.326t.128.332t.112.337q.051.171.095.343q.043.173.078.348q.034.174.061.35t.043.353q.018.177.026.355t.009.356c0 .948-.189 1.885-.514 2.801");
}

</style>
