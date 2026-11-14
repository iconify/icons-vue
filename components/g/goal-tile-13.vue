<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2t816boz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:goal-tile-13" /></template>
<style>
.b2t816boz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.25 2.25h7.5q2.485 0 4.243 1.757Q21.75 5.765 21.75 8.25v7.5q0 2.485-1.757 4.243q-1.758 1.757-4.243 1.757h-7.5q-2.485 0-4.243-1.757Q2.25 18.235 2.25 15.75v-7.5q0-2.485 1.757-4.243Q5.765 2.25 8.25 2.25M7.227 7.227Q5.25 9.204 5.25 12t1.977 4.773T12 18.75t4.773-1.977T18.75 12t-1.977-4.773T12 5.25T7.227 7.227");
}

</style>
