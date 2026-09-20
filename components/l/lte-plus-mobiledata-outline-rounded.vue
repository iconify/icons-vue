<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxekqw-yz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:lte-plus-mobiledata-outline-rounded" /></template>
<style>
.qxekqw-yz {
  fill: currentColor;
  d: path("M5.25 15.5h-3q-.213 0-.356-.144T1.75 15V9q0-.213.144-.356t.357-.144t.356.144T2.75 9v5.5h2.5q.213 0 .356.144t.144.357t-.144.356t-.356.143m2.836-.144q-.144-.144-.144-.356V9.5h-1.5q-.212 0-.356-.144t-.144-.357t.144-.356t.356-.143h4q.213 0 .357.144t.143.357t-.143.356t-.357.143h-1.5V15q0 .213-.144.356q-.143.144-.356.144t-.356-.144m8.01.144h-3q-.212 0-.356-.144T12.596 15V9q0-.213.144-.356t.356-.144h3q.213 0 .357.144t.143.357t-.143.356t-.357.143h-2.5v2h2.5q.213 0 .357.144t.143.357t-.143.356t-.357.143h-2.5v2h2.5q.213 0 .357.144t.143.357t-.143.356t-.357.143m4.154-3h-1.5q-.213 0-.356-.144t-.144-.357t.144-.356t.356-.143h1.5V10q0-.213.144-.356t.357-.144t.356.144t.143.356v1.5h1.5q.213 0 .356.144t.144.357t-.144.356t-.356.143h-1.5V14q0 .213-.144.356t-.357.144t-.356-.144T20.25 14z");
}

</style>
