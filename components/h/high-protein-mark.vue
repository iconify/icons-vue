<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="te2oocczv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:high-protein-mark" /></template>
<style>
.te2oocczv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.75 3.25h-7.5q-2.485 0-4.243 1.757Q2.25 6.765 2.25 9.25v5.5q0 2.485 1.757 4.243Q5.765 20.75 8.25 20.75h7.5q2.485 0 4.243-1.757q1.757-1.758 1.757-4.243v-5.5q0-2.485-1.757-4.243Q18.235 3.25 15.75 3.25M7.5 7.5q2.25 0 2.25 2.25v1.5h4.5v-1.5q0-2.25 2.25-2.25t2.25 2.25v4.5q0 2.25-2.25 2.25t-2.25-2.25v-1.5h-4.5v1.5q0 2.25-2.25 2.25t-2.25-2.25v-4.5q0-2.25 2.25-2.25");
}

</style>
