<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qerbupbry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-rectangle" /></template>
<style>
.qerbupbry {
  fill: currentColor;
  d: path("M2 4h20v16H2z");
}

</style>
