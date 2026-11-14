<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="df0rjmbsc"/><path class="rwsc6jb3y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:last-lap-bell" /></template>
<style>
.df0rjmbsc {
  d: path("M13.25 14.5H3C4.5 13 5 11 5 9q0-.123.006-.245q.006-.123.018-.245t.03-.244t.042-.241q.024-.121.054-.24t.065-.236q.036-.118.077-.233q.042-.116.089-.229q.047-.114.099-.225t.11-.219t.121-.214t.132-.207t.141-.2t.151-.194t.16-.186q.083-.091.169-.178q.087-.086.178-.169q.091-.082.186-.16t.194-.151q.098-.073.2-.141q.102-.069.207-.132q.106-.063.214-.121t.219-.11t.225-.099t.229-.089t.233-.077t.236-.065t.24-.054q.12-.024.241-.042q.122-.018.244-.03t.245-.018T10 4t.245.006t.245.018t.244.03t.241.042q.121.024.24.054t.236.065t.233.077t.229.089q.114.047.225.099t.219.11t.214.121t.207.132t.2.141t.194.151t.186.16q.091.083.178.169q.086.087.169.178q.082.091.16.186t.151.194q.073.098.141.2q.069.102.132.207q.063.106.121.214t.11.219t.099.225t.089.229t.077.233t.065.236t.054.24q.024.12.042.241q.018.122.03.244t.018.245T15 9c0 .916.105 1.833.363 2.701M10 2.5V4M8 17a2 2 0 0 0 4 0m4 4.75V14.5h5.5V19H16");
}

.rwsc6jb3y {
  fill: currentColor;
  d: path("M16 14.5h2.75v2.25H16Zm2.75 2.25h2.75V19h-2.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
