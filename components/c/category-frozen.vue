<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="teta1kbvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:category-frozen" /></template>
<style>
.teta1kbvs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 2h17v20h-17Zm14 3v14m-7-12v10m4.33-7.5l-8.66 5m8.66 0l-8.66-5m4.33-.75L9.25 7.5m1.25 1.25l1.25-1.25m1.565 2.875l.457-1.708m-.457 1.708l1.707.458m-1.707 2.792l1.707-.458m-1.707.458l.457 1.708M10.5 15.25l1.25 1.25m-1.25-1.25L9.25 16.5m-1.565-2.875l-.457 1.708m.457-1.708l-1.707-.458m1.707-2.792l-1.707.458m1.707-.458l-.457-1.708");
}

</style>
