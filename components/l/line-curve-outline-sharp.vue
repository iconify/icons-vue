<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qpbm6-b1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:line-curve-outline-sharp" /></template>
<style>
.qpbm6-b1v {
  fill: currentColor;
  d: path("M18 20q0-2.9-1.1-5.45t-3-4.45t-4.45-3T4 6V5q3.108 0 5.838 1.176t4.77 3.216t3.216 4.77T19 20z");
}

</style>
