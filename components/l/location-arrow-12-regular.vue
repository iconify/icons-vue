<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="jp2duubyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:location-arrow-12-regular" /></template>
<style>
.jp2duubyt {
  fill: currentColor;
  d: path("M10.932 2.361c.31-.809-.484-1.603-1.293-1.292L1.642 4.145c-.906.348-.834 1.653.105 1.9l3.05.803a.5.5 0 0 1 .356.356l.802 3.05c.247.939 1.552 1.01 1.9.104zm-.934-.359L6.922 10L6.12 6.95a1.5 1.5 0 0 0-1.07-1.068l-3.049-.803z");
}

</style>
