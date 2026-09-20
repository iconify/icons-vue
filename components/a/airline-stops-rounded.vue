<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yybomwbed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:airline-stops-rounded" /></template>
<style>
.yybomwbed {
  fill: currentColor;
  d: path("M11.48 17q-.1-3.54-2.35-6.141T3.523 8.017q-.22-.011-.371-.157Q3 7.714 3 7.5t.166-.357t.398-.112q3.002.217 5.293 2.175T12 14.108q.777-2.372 2.471-4.146T18.36 7h-3.572q-.213 0-.356-.143t-.144-.357t.144-.357t.356-.143h4.404q.349 0 .578.23t.23.578v4.404q0 .213-.143.356t-.357.144t-.357-.144t-.143-.356V7.796q-2.71 1.425-4.577 3.804T12.481 17h1.365q.213 0 .357.143q.143.143.143.357t-.143.357t-.357.143h-3.75q-.213 0-.357-.143t-.143-.357t.144-.357t.356-.143z");
}

</style>
