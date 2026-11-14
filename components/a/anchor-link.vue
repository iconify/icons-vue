<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ab1bysbrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:anchor-link" /></template>
<style>
.ab1bysbrd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 4.5H7a4 4 0 0 0 0 8h1.5m5-8H15q.197 0 .392.019q.196.02.388.058q.193.038.381.095t.37.132t.355.168t.336.202q.164.109.316.234q.151.125.29.264t.264.29t.234.316q.109.163.202.336q.092.174.168.355q.075.182.132.37t.095.381t.058.388Q19 8.303 19 8.5q0 .152-.012.304q-.011.151-.034.302q-.023.15-.057.298q-.035.148-.08.293q-.046.145-.102.286q-.057.142-.124.278t-.144.268t-.164.256q-.086.124-.183.242q-.096.118-.2.228t-.218.213q-.113.101-.233.195q-.12.093-.247.176q-.127.084-.26.158t-.271.137t-.281.117m-1.066.236q-.162.013-.324.013h-1.5M8 8.5h6m2.5 6.5v6.5m3-6.5v6.5m-4.75-4.75h6.5m-6.5 3h6.5");
}

</style>
