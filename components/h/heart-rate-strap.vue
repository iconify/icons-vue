<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pxrmtwb6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:heart-rate-strap" /></template>
<style>
.pxrmtwb6h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M20.298 9.599q.14.104.266.224t.238.253q.112.134.207.28q.096.146.174.301q.078.156.137.32t.1.333q.04.17.06.343t.02.347q0 .133-.012.265q-.012.133-.035.264t-.058.259t-.081.253t-.103.245t-.125.234t-.144.223q-.078.108-.164.209t-.182.194t-.198.177t-.213.159t-.226.139t-.238.119q-.121.054-.247.097q-.125.044-.254.075q-.13.032-.261.053m-13.852.009q-.134-.017-.265-.047q-.132-.03-.261-.071q-.128-.041-.253-.094q-.124-.053-.243-.117q-.119-.063-.232-.137t-.219-.159q-.105-.084-.203-.177t-.187-.194t-.168-.211t-.149-.225t-.129-.238q-.058-.121-.106-.248q-.047-.126-.083-.256t-.061-.263t-.036-.267T2.5 12q0-.17.019-.338q.019-.169.057-.334t.094-.325t.131-.312q.074-.153.165-.296q.09-.143.197-.276q.106-.132.226-.251t.254-.224M12 18.5c-3-2.5-5.5-4.75-5.5-8a3 3 0 0 1 5.5-2a3 3 0 0 1 5.5 2c0 3.25-2.5 5.5-5.5 8");
}

</style>
