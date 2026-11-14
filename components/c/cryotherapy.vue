<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l202ihlaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cryotherapy" /></template>
<style>
.l202ihlaj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13 19.793V21.5H3V8q0-.123.006-.245q.006-.123.018-.245t.03-.244t.042-.241q.024-.121.054-.24t.065-.236q.036-.118.077-.233q.042-.116.089-.229q.047-.114.099-.225t.11-.219t.121-.214t.132-.207t.141-.2q.073-.099.151-.194t.16-.186t.169-.178t.178-.169t.186-.16t.194-.151q.098-.073.2-.141q.102-.069.207-.132q.106-.063.214-.121t.219-.11t.225-.099t.229-.089t.233-.077t.236-.065t.24-.054q.12-.024.241-.042q.122-.018.244-.03t.245-.018Q7.877 3 8 3t.245.006q.123.006.245.018t.244.03t.241.042q.121.024.24.054t.236.065t.233.077t.229.089t.225.099t.219.11t.214.121q.105.063.207.132q.102.068.2.141t.194.151q.095.078.186.16q.091.083.178.169q.086.087.169.178q.082.091.16.186t.151.194q.073.098.141.2q.069.102.132.207q.063.106.121.214t.11.219t.099.225t.089.229t.077.233t.065.236t.054.24q.024.12.042.241q.018.122.03.244t.018.245Q13 7.877 13 8v7.693M8 3v18.5m10.75-7V21m2.815-4.875l-5.63 3.25m5.63 0l-5.63-3.25");
}

</style>
