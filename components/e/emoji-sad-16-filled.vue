<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l3qw1bsqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:emoji-sad-16-filled" /></template>
<style>
.l3qw1bsqa {
  fill: currentColor;
  d: path("M8 2a6 6 0 1 1 0 12A6 6 0 0 1 8 2M6.25 7.5a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5m3.5 0a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5m.118 3.322a.5.5 0 1 0 .764-.644c-1.325-1.57-3.94-1.57-5.264 0a.5.5 0 1 0 .764.644c.925-1.096 2.81-1.096 3.736 0");
}

</style>
