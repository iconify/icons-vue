<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vl4n_u1sg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:breakout-room-16-filled" /></template>
<style>
.vl4n_u1sg {
  fill: currentColor;
  d: path("M6.5 7A2.5 2.5 0 0 1 9 9.5v2A2.5 2.5 0 0 1 6.5 14h-2A2.5 2.5 0 0 1 2 11.5v-2A2.5 2.5 0 0 1 4.5 7zm5-5A2.5 2.5 0 0 1 14 4.5v7a2.5 2.5 0 0 1-2.5 2.5H8.948A3.5 3.5 0 0 0 10 11.5v-2A3.5 3.5 0 0 0 6.5 6h-2c-.98 0-1.865.403-2.5 1.052V4.5A2.5 2.5 0 0 1 4.5 2z");
}

</style>
