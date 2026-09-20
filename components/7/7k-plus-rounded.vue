<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-83kvbzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:7k-plus-rounded" /></template>
<style>
.r-83kvbzm {
  fill: currentColor;
  d: path("M9.054 10.192L7.729 14.08q-.068.227.057.42t.377.193q.16 0 .27-.085t.165-.245l1.41-4.139q.13-.346-.083-.63t-.56-.285h-2.75q-.19 0-.316.126t-.126.316t.126.316t.316.126zm2.984 2.135l2.166 2.225q.05.056.319.14q.29 0 .404-.262t-.085-.478l-1.938-1.99l1.963-1.958q.198-.196.075-.446t-.4-.25q-.079 0-.158.036q-.08.037-.142.104l-2.204 2.187V9.75q0-.19-.126-.316t-.316-.126t-.316.126t-.126.316v4.5q0 .19.126.316t.316.126t.316-.126t.126-.316zm4.693.058V13.5q0 .162.111.273t.274.112t.273-.112t.111-.273v-1.115h1.116q.161 0 .273-.112T19 12t-.111-.273t-.273-.111H17.5V10.5q0-.161-.111-.273t-.273-.111t-.274.111t-.111.273v1.116h-1.116q-.161 0-.273.111t-.111.273t.111.273t.273.112zM5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20z");
}

</style>
