<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wni-bqfan"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:drive-shaft" /></template>
<style>
.wni-bqfan {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.24 8.75q-.12-1.5-1.74-1.5q-1.75 0-1.75 1.75v6q0 1.75 1.75 1.75q1.62 0 1.74-1.5H6.5q2.85 0 3.201-2.5h4.598q.351 2.5 3.201 2.5h1.26q.12 1.5 1.74 1.5q1.75 0 1.75-1.75V9q0-1.75-1.75-1.75q-1.62 0-1.74 1.5H17.5q-2.85 0-3.201 2.5H9.701Q9.35 8.75 6.5 8.75zm1.26 1.5q1.75 0 1.75 1.75T6.5 13.75H5.25v-3.5zm11 3.5q-1.75 0-1.75-1.75t1.75-1.75h1.25v3.5z");
}

</style>
