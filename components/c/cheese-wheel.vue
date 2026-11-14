<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j48jt42cd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cheese-wheel" /></template>
<style>
.j48jt42cd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.551 11.741L13.713 9.75h6.037v4.5h-4v-2.005q0-.055-.009-.11q-.035-.226-.19-.394M14.25 14.25h-1.5v-1.026q.746-.03 1.5-.116zm-3 .75q0 .141.051.273q.052.132.148.236l2.005 2.172q-3.194.268-6.06-.542Q4.272 16.257 4.25 15v-3.611q1.288.906 3.62 1.414q1.668.363 3.38.424zm2.463.75h.537v.582zm2.037 2.5v-2.5h4.75q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V9.006q.031-2.104-3.314-3.34q-2.994-1.106-6.951-.917q-3.99.191-6.34 1.58Q2.362 7.677 2.75 9.352V15q.041 2.397 4.236 3.583q3.816 1.078 8.129.408q.226-.035.394-.19l.001-.001q.115-.106.177-.25q.063-.143.063-.3");
}

</style>
