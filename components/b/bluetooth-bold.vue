<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="r-qq57b4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:bluetooth-bold" /></template>
<style>
.r-qq57b4c {
  fill: currentColor;
  d: path("M199.2 166.4L148 128l51.2-38.4a12 12 0 0 0 0-19.2l-64-48A12 12 0 0 0 116 32v72L71.2 70.4a12 12 0 0 0-14.4 19.2L108 128l-51.2 38.4a12 12 0 1 0 14.4 19.2L116 152v72a12 12 0 0 0 19.2 9.6l64-48a12 12 0 0 0 0-19.2M140 56l32 24l-32 24Zm0 144v-48l32 24Z");
}

</style>
