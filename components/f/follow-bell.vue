<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hyrrp0bjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:follow-bell" /></template>
<style>
.hyrrp0bjm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.818 5.068Q4.5 6.386 4.5 8.25t1.318 3.182T9 12.75t3.182-1.318T13.5 8.25t-1.318-3.182T9 3.75T5.818 5.068m16.306 8.266l-.374-.561V10.5q0-1.346-.952-2.298T18.5 7.25q-3.25 0-3.25 3.25v2.273l-.374.561q-.126.189-.126.416q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h6q.227 0 .416-.126q.061-.041.114-.093q.052-.052.093-.114q.041-.061.07-.129q.028-.068.042-.141t.015-.146t-.014-.147q-.015-.072-.043-.14t-.069-.13M1.75 20q0-2.427 2.213-4.015Q6.03 14.5 9 14.5t5.037 1.485Q16.25 17.573 16.25 20q0 1.75-1.75 1.75h-11q-1.75 0-1.75-1.75");
}

</style>
