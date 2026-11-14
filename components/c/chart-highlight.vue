<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lwlzsybrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chart-highlight" /></template>
<style>
.lwlzsybrw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.5 4.5q0-2.25-2.25-2.25T13 4.5v15q0 2.25 2.25 2.25t2.25-2.25zm-7.75.75Q12 5.25 12 7.5v12q0 2.25-2.25 2.25T7.5 19.5v-12q0-2.25 2.25-2.25m10.75 3q2 0 2 2v9.5q0 .828-.586 1.414t-1.414.586t-1.414-.586t-.586-1.414v-9.5q0-2 2-2m-14 4.25q0-2.25-2.25-2.25T2 12.5v7q0 2.25 2.25 2.25T6.5 19.5z");
}

</style>
