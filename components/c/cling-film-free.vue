<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ictz05bek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cling-film-free" /></template>
<style>
.ictz05bek {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.527 7.461q.013.159.03.315t.041.307t.051.297t.061.285t.071.27t.08.255t.088.236t.096.216t.103.195q.054.092.11.172t.115.148t.12.122t.123.096t.127.069q.063.028.128.042q.064.014.129.014q.227 0 .444-.168q.216-.168.404-.488M6.9 3H19q.074 0 .147.018t.146.054q.072.036.142.089q.071.054.139.124t.133.158t.126.189q.062.102.119.219t.109.247q.052.131.099.273q.046.142.087.296q.041.153.076.315q.035.163.063.333t.049.346t.036.357t.022.364q.007.184.007.368t-.007.368q-.007.183-.022.364q-.014.18-.036.357q-.021.176-.049.346t-.063.333t-.076.315q-.041.154-.087.296q-.047.142-.099.273q-.052.13-.109.247t-.119.219t-.126.189t-.133.158t-.139.124t-.142.089q-.073.036-.146.054T19 10.5h-4.571m-7.9 0H5m3.5 1.9v3.1L10 17l1.5-1.5L13 17l.025-.025m4.475-3.447V10.5m-14-7l17 17");
}

</style>
