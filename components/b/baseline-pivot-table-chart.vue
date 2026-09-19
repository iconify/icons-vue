<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lkq-g2b6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-pivot-table-chart" /></template>
<style>
.lkq-g2b6b {
  fill: currentColor;
  d: path("M10 8h11V5c0-1.1-.9-2-2-2h-9zM3 8h5V3H5c-1.1 0-2 .9-2 2zm2 13h3V10H3v9c0 1.1.9 2 2 2m8 1l-4-4l4-4zm1-9l4-4l4 4zm.58 6H13v-2h1.58c1.33 0 2.42-1.08 2.42-2.42V13h2v1.58c0 2.44-1.98 4.42-4.42 4.42");
}

</style>
