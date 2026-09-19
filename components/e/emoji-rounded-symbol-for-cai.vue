<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nmbx1oz1t"/><path class="tjo19acds"/><path class="fq1d9j89n"/><path class="ixwmfub7s"/><path class="k-ox03dns"/><path class="gnnfasbnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-rounded-symbol-for-cai" /></template>
<style>
.fq1d9j89n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.857 7.491a17.66 17.66 0 0 0-11.134 12.67h7.295V14.4a13.8 13.8 0 0 0-1.92 2.304m18.045-9.213V40.51a17.66 17.66 0 0 0 11.134-12.67h-7.295v5.76a13.8 13.8 0 0 0 1.92-2.304");
}

.gnnfasbnr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.696 16.321h4.607V31.68h-4.607z");
}

.ixwmfub7s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.143 7.491a17.66 17.66 0 0 1 11.134 12.67h-7.295V14.4a13.8 13.8 0 0 1 1.92 2.304");
}

.k-ox03dns {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M2.5 24c0 11.874 9.626 21.5 21.5 21.5S45.5 35.874 45.5 24S35.874 2.5 24 2.5S2.5 12.126 2.5 24");
}

.nmbx1oz1t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.857 12.482h3.84V6.34h4.607v6.143h3.839M17.857 35.518h3.84v6.143h4.607v-6.143h3.839m0-11.518H41.66m-23.803 0H6.34");
}

.tjo19acds {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.857 7.491V40.51A17.66 17.66 0 0 1 6.723 27.84h7.295v5.76a13.8 13.8 0 0 1-1.92-2.304");
}

</style>
