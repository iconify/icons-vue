<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sm1ij717i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:camera-obscura" /></template>
<style>
.sm1ij717i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.25 2.75h11.5q1.036 0 1.768.732q.158.158.282.331q-.153-.067-.32-.063q-.166.005-.315.079L6.5 11.161l-.75-.375V5.25q0-2.5 2.5-2.5m-2.5 10.464l.75-.375l14.665 7.332q.149.074.315.079q.167.004.32-.063q-.124.173-.282.331q-.732.732-1.768.732H8.25q-2.5 0-2.5-2.5zM8.177 12l13.658-6.829q.129-.065.225-.172q.096-.108.145-.243q.045.238.045.494v13.5q0 .256-.045.494q-.049-.135-.145-.243t-.225-.172z");
}

</style>
