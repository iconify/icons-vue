<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxjm91brf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:carousel-dots" /></template>
<style>
.bxjm91brf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14 10q-2 0-2 2t2 2t2-2t-2-2m3.5 2q0-2 2-2t2 2t-2 2t-2-2M4.25 10.25h4.5q1.75 0 1.75 1.75t-1.75 1.75h-4.5Q2.5 13.75 2.5 12t1.75-1.75");
}

</style>
