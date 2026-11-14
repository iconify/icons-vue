<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="spi4k6bzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:block-storage" /></template>
<style>
.spi4k6bzf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.5 2.75h5q1.036 0 1.768.732T17 5.25v5q0 .541-.2 1h1.95q2.5 0 2.5 2.5v5q0 2.5-2.5 2.5h-5q-1.236 0-1.861-.611q-.693.611-1.639.611h-5q-2.5 0-2.5-2.5v-5q0-2.5 2.5-2.5H7.2q-.2-.459-.2-1v-5q0-2.5 2.5-2.5");
}

</style>
