<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v680tt11v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:emergency-appeal" /></template>
<style>
.v680tt11v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 7.5h3l6.5-4V16L7 12H4a1.5 1.5 0 0 1-1.5-1.5V9A1.5 1.5 0 0 1 4 7.5ZM6 12l1.25 5.5m9-10.25q.109.107.208.223q.099.115.188.239t.167.256q.077.131.143.268q.066.138.12.28t.095.29t.069.297t.043.301t.017.305q.002.152-.009.304q-.012.152-.036.303q-.025.15-.063.298q-.037.148-.088.292t-.113.283t-.137.272t-.16.259M18.75 4.5q.153.183.294.375q.14.193.268.395q.127.202.24.412t.211.427q.099.218.182.441q.084.223.152.452t.12.461q.053.233.089.469q.037.236.057.473q.02.238.024.477q.004.238-.008.476q-.012.239-.041.475q-.028.237-.073.472q-.044.234-.104.465q-.061.231-.137.457q-.075.226-.167.446M18 14.5V18m0 3h.01");
}

</style>
