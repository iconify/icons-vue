<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="nerijcc5y"/><path class="fsxwe0nbu"/><path class="girv7pn6s"/><path class="n-dhbzbjq"/><path class="ko6o-6b9b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:full-screen-circle-broken" /></template>
<style>
.fsxwe0nbu {
  d: path("M6 14.0002C6.01447 15.7067 6.10921 16.6475 6.72963 17.2679C7.35004 17.8883 8.29083 17.9831 9.99739 17.9976");
}

.girv7pn6s {
  d: path("M17.998 9.99739C17.9836 8.29083 17.8888 7.35004 17.2684 6.72963C16.648 6.10921 15.7072 6.01447 14.0007 6");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ko6o-6b9b {
  d: path("M7 3.33782C8.47087 2.48697 10.1786 2 12 2C17.5228 2 22 6.47715 22 12C22 17.5228 17.5228 22 12 22C6.47715 22 2 17.5228 2 12C2 10.1786 2.48697 8.47087 3.33782 7");
}

.n-dhbzbjq {
  d: path("M17.998 14.0002C17.9836 15.7067 17.8888 16.6475 17.2684 17.2679C16.648 17.8883 15.7072 17.9831 14.0007 17.9976");
}

.nerijcc5y {
  d: path("M6 9.99739C6.01447 8.29083 6.10921 7.35004 6.72963 6.72963C7.35004 6.10921 8.29083 6.01447 9.99739 6");
}

</style>
