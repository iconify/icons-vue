<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ap_3h3b3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:clapperboard-play" /></template>
<style>
.ap_3h3b3k {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 5v13.5q0 2.75 2.75 2.75h14q2.75 0 2.75-2.75V5q0-2.25-2.25-2.25h-15Q2.25 2.75 2.25 5m6.536-.75l-1.25 2.5H3.75V5q0-.75.75-.75zm1.678 0h4.322l-1.25 2.5H9.214zm6 0H19.5q.75 0 .75.75v1.75h-5.036zm-3.738 7.377l.748.486q1.024.665 1.024 1.887t-1.025 1.887l-.747.486q-1.123.729-2.3.09q-1.176-.638-1.176-1.977v-.972q0-1.339 1.176-1.977q1.177-.639 2.3.09");
}

</style>
