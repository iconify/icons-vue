<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ru9z57_4l"/><path class="ulv0ikb_p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:animal-health" /></template>
<style>
.ru9z57_4l {
  d: path("M8 14.25L7 5.5h8l-.919 8.041");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ulv0ikb_p {
  d: path("M13.44 14.043q-.536-.265-1.161-.404Q11.655 13.5 11 13.5q-.209 0-.417.014q-.207.015-.412.044t-.405.071t-.392.099t-.377.126q-.185.07-.358.152q-.174.081-.335.175t-.309.198t-.28.218t-.249.236t-.214.253q-.099.13-.178.266q-.08.136-.141.277t-.101.286q-.041.144-.062.291t-.02.294q0 .147.02.294q.021.147.062.291q.04.145.101.286t.141.277q.079.136.178.266t.214.253t.249.236q.132.114.28.218q.147.105.309.198q.161.094.335.175q.173.082.358.152q.184.069.377.126q.192.056.392.099t.405.071t.412.044q.208.014.417.014q.892 0 1.708-.253M7 5.5c-2.25 0-3.5-1.25-3.5-3m11.5 3c2.25 0 3.5-1.25 3.5-3m-11.25 5q-4.75.25-4 2q1.75 1 4.25.75m7.25-2.75q4.75.25 4 2q-1.75 1-4.25.75m4 11.25c-2-1.5-3.5-2.75-3.5-4.25c0-1.75 2.5-2.5 3.5-.75c1-1.75 3.5-1 3.5.75c0 1.5-1.5 2.75-3.5 4.25Z");
}

</style>
