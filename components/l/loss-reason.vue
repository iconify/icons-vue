<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kel_1bbfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:loss-reason" /></template>
<style>
.kel_1bbfu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 3zA1.75 1.75 0 0 1 6 4.75v14.5A1.75 1.75 0 0 1 4.25 21a1.75 1.75 0 0 1-1.75-1.75V4.75A1.75 1.75 0 0 1 4.25 3m6.25 5za1.75 1.75 0 0 1 1.75 1.75v9.5A1.75 1.75 0 0 1 10.5 21a1.75 1.75 0 0 1-1.75-1.75v-9.5A1.75 1.75 0 0 1 10.5 8m4.5 7.475v-.725q0-.269.081-.526t.235-.477M18 14.5V21m-2.75-2.75L18 21l2.75-2.75");
}

</style>
