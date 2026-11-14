<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kib8v-vas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:conflict-of-interest" /></template>
<style>
.kib8v-vas {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.5v17m-3.25 0h6.4M5.5 10l13-5M3 14.5L5.5 10L8 14.5H3a2.5 2.5 0 0 0 5 0m8-5L18.5 5L21 9.5h-5q0 .169.023.337t.068.331t.112.319t.154.301t.194.277t.228.249q.123.116.261.215q.137.099.287.179m2.304.022q.154-.078.295-.177q.142-.098.269-.215q.126-.117.236-.25t.199-.28q.091-.147.16-.305q.069-.157.116-.323t.07-.337Q21 9.672 21 9.5m-3 5V18m0 3h.01");
}

</style>
