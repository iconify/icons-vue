<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="mvaf7qbbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-circle-left-12-filled" /></template>
<style>
.mvaf7qbbt {
  fill: currentColor;
  d: path("M6 1a5 5 0 1 0 0 10A5 5 0 0 0 6 1m-.098 2.646a.5.5 0 0 1 0 .708L4.756 5.5H8.5a.5.5 0 0 1 0 1H4.756l1.146 1.146a.5.5 0 1 1-.707.708l-2-2a.5.5 0 0 1 0-.708l2-2a.5.5 0 0 1 .707 0");
}

</style>
