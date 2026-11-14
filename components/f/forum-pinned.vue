<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yrelbccos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:forum-pinned" /></template>
<style>
.yrelbccos {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.875 10h10.25a4.375 4.375 0 0 1 4.375 4.375v2.75a4.375 4.375 0 0 1-4.375 4.375H6.875A4.375 4.375 0 0 1 2.5 17.125v-2.75A4.375 4.375 0 0 1 6.875 10m7.683-4.154l2.265 1.057a.625.625 0 0 0 .876-.695l-.154-.734a1.5 1.5 0 0 1 .108-.942l.212-.454a1 1 0 0 0-.484-1.328a1 1 0 0 0-1.329.483l-.211.453a1.5 1.5 0 0 1-.653.689l-.661.354a.625.625 0 0 0 .031 1.117M14 10l1.69-3.625M6.5 14.25h11m-11 3.5h6");
}

</style>
