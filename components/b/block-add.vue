<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="luw78-1op"/><path class="bwljf1bmn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:block-add" /></template>
<style>
.bwljf1bmn {
  d: path("m3.5 7.5l8.5 5l8.5-5m-8.5 5v9m6-6.5v6m-3-3h6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.luw78-1op {
  d: path("m13.694 20.503l-.807.475q-.1.059-.208.104t-.219.076q-.113.031-.228.046q-.116.015-.232.015t-.232-.015t-.228-.046t-.219-.076q-.108-.045-.208-.104l-6.75-3.971q-.098-.058-.188-.128q-.09-.069-.17-.15t-.149-.172t-.125-.189t-.1-.204t-.072-.216t-.044-.222t-.015-.227V8.501q0-.114.015-.227q.015-.112.044-.222t.072-.216q.044-.105.1-.204t.125-.189t.149-.172t.17-.15q.09-.07.188-.128l6.75-3.971q.1-.059.208-.104t.219-.076q.113-.031.228-.046q.116-.015.232-.015t.232.015t.228.046t.219.076q.108.045.208.104l6.75 3.971q.098.058.188.128q.09.069.17.15t.149.172t.125.189t.1.204q.043.106.072.216t.044.222t.015.227v5.331");
}

</style>
