<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l23_aqbma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:lte-mobiledata-outline-rounded" /></template>
<style>
.l23_aqbma {
  fill: currentColor;
  d: path("M5.154 15V9q0-.213.144-.356t.357-.144t.356.144t.143.356v5.5h2.5q.212 0 .356.144t.144.357t-.144.356t-.356.143h-3q-.213 0-.356-.144T5.154 15m6.577-5.5h-1.5q-.213 0-.356-.144t-.144-.357t.144-.356t.356-.143h4q.212 0 .356.144t.144.357t-.144.356t-.356.143h-1.5V15q0 .213-.144.356q-.144.144-.357.144t-.356-.144t-.143-.356zM16.5 15V9q0-.213.144-.356T17 8.5h3q.213 0 .356.144t.144.357t-.144.356T20 9.5h-2.5v2H20q.213 0 .356.144t.144.357t-.144.356T20 12.5h-2.5v2H20q.213 0 .356.144t.144.357t-.144.356T20 15.5h-3q-.213 0-.356-.144T16.5 15");
}

</style>
