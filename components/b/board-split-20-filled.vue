<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="maf7u1bjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:board-split-20-filled" /></template>
<style>
.maf7u1bjg {
  fill: currentColor;
  d: path("M6 3a3 3 0 0 0-3 3v3h8V3zm5 7H3v4a3 3 0 0 0 3 3h5zm3 7h-2v-4h5v1a3 3 0 0 1-3 3m3-5h-5V8h5zm0-5h-5V3h2a3 3 0 0 1 3 3z");
}

</style>
