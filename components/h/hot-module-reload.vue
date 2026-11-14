<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="moaw-0pvt"/><path class="j-o94nbsa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hot-module-reload" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j-o94nbsa {
  d: path("m2 7l8 4.5L18 7m-8 4.5V20m10.5-7l-4 4.5h4L16.75 22");
}

.moaw-0pvt {
  d: path("m13.759 17.885l-2.901 1.632q-.098.055-.202.097t-.213.071q-.108.028-.219.042q-.112.015-.224.015t-.224-.015q-.111-.014-.219-.042q-.109-.029-.213-.071t-.202-.097l-6.25-3.515q-.101-.057-.194-.126q-.092-.07-.175-.151q-.083-.082-.154-.173q-.071-.092-.13-.192q-.058-.1-.103-.207t-.075-.218t-.046-.227T2 14.477V8.023q0-.116.015-.231q.016-.115.046-.227q.03-.111.075-.218t.103-.207q.059-.1.13-.192q.071-.091.154-.173t.175-.151t.194-.126l6.25-3.515q.098-.055.202-.097t.213-.071q.108-.028.219-.042q.112-.015.224-.015t.224.015q.111.014.219.042q.109.029.213.071t.202.097l6.25 3.515q.101.057.194.126q.092.07.175.151q.083.082.154.173q.071.092.13.192q.058.1.103.207t.075.218q.03.112.046.227q.015.115.015.231v3.563");
}

</style>
