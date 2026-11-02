<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zpw68zb-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:diamond-fill-round" /></template>
<style>
.zpw68zb-y {
  fill: currentColor;
  d: path("M15.707 20.707a5.243 5.243 0 0 1-7.414 0l-5-5a5.243 5.243 0 0 1 0-7.414l5-5a5.243 5.243 0 0 1 7.414 0l5 5a5.243 5.243 0 0 1 0 7.414Z");
}

</style>
