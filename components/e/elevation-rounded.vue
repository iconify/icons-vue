<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m0ne-ybxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:elevation-rounded" /></template>
<style>
.m0ne-ybxa {
  fill: currentColor;
  d: path("M19 21H4q-.625 0-.888-.537t.088-1.038l4.7-6.6q.275-.4.7-.612T9.525 12h4.025l5.7-6.65q.45-.525 1.1-.288T21 6v13q0 .825-.587 1.413T19 21M7.5 10l-3.1 4.375q-.25.35-.65.413T3 14.6t-.412-.65t.187-.75L5.9 8.85q.275-.4.7-.625T7.525 8h4.025l4.05-4.725q.275-.325.675-.35t.725.25t.35.675t-.25.725L13.05 9.3q-.275.35-.675.525T11.55 10z");
}

</style>
