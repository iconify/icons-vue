<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjtf5_bzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:anchor-down" /></template>
<style>
.jjtf5_bzw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m2 2v12.25M6 9.5h6m-8 4.25q0 .123.006.245q.006.123.018.245t.03.244t.042.241q.024.121.054.24t.065.236t.077.233t.089.229q.047.114.099.225t.11.219t.121.214t.132.207t.141.2t.151.194t.16.186t.169.178q.087.086.178.169q.091.082.186.16t.194.151q.098.073.2.141q.102.069.207.132q.106.063.214.121t.219.11t.225.099t.229.089t.233.077t.236.065t.24.054q.12.024.241.042q.122.018.244.03t.245.018t.245.006q.267 0 .533-.029q.266-.028.527-.085q.261-.056.515-.141t.497-.194q.243-.111.473-.247t.445-.296t.41-.342t.371-.383m.561-.786q.328-.569.498-1.205q.17-.635.17-1.292m4 .75V21m-2.75-2.75L18 21l2.75-2.75");
}

</style>
