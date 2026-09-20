<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qbe4bjb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:desktop-cursor-20-filled" /></template>
<style>
.qbe4bjb2m {
  fill: currentColor;
  d: path("M3.5 2A1.5 1.5 0 0 0 2 3.5v10A1.5 1.5 0 0 0 3.5 15H7v2H5.5a.5.5 0 0 0 0 1H11l.001-1H8v-2h3.002l.003-4.5a1.5 1.5 0 0 1 2.556-1.065l4.408 4.368q.03-.148.031-.303v-10A1.5 1.5 0 0 0 16.5 2zm9.357 8.145a.5.5 0 0 0-.852.355L12 18.498a.5.5 0 0 0 .9.301l1.995-2.646l3.496.776a.5.5 0 0 0 .46-.844z");
}

</style>
