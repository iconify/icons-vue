<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_7c-cbjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:crochet-granny-square" /></template>
<style>
.r_7c-cbjx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.793 3.793Q1.251 4.126 1.251 7q0 1.688.877 2.499q-.878.812-.878 2.501t.878 2.5q-.878.811-.878 2.5q0 2.875 2.544 3.207q.332 2.542 3.206 2.542q1.688 0 2.499-.877q.812.878 2.501.878t2.5-.878q.811.878 2.5.878q2.875 0 3.207-2.543Q22.75 19.875 22.75 17q0-1.689-.878-2.5q.878-.811.878-2.5t-.878-2.501q.877-.811.877-2.499q0-2.874-2.542-3.206Q19.875 1.25 17 1.25q-1.689 0-2.5.878q-.811-.878-2.5-.878t-2.501.878Q8.688 1.251 7 1.251q-2.874 0-3.207 2.542M7.25 9.75q0-2.5 2.5-2.5h4.5q2.5 0 2.5 2.5v4.5q0 2.5-2.5 2.5h-4.5q-2.5 0-2.5-2.5z");
}

</style>
