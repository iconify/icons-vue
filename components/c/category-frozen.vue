<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zgy4udqqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:category-frozen" /></template>
<style>
.zgy4udqqg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 2h10a3.5 3.5 0 0 1 3.5 3.5v13A3.5 3.5 0 0 1 17 22H7a3.5 3.5 0 0 1-3.5-3.5v-13A3.5 3.5 0 0 1 7 2m10.5 3v14m-7-12v10m4.33-7.5l-8.66 5m8.66 0l-8.66-5m4.33-.75L9.25 7.5m1.25 1.25l1.25-1.25m1.565 2.875l.457-1.708m-.457 1.708l1.707.458m-1.707 2.792l1.707-.458m-1.707.458l.457 1.708M10.5 15.25l1.25 1.25m-1.25-1.25L9.25 16.5m-1.565-2.875l-.457 1.708m.457-1.708l-1.707-.458m1.707-2.792l-1.707.458m1.707-.458l-.457-1.708");
}

</style>
