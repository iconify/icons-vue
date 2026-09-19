<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wj5xh-b7b"/><path class="nbywah_li"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-money" /></template>
<style>
.nbywah_li {
  fill: currentColor;
  d: path("M2 4v16h20V4zm2 14V6h16v12z");
}

.wj5xh-b7b {
  fill: currentColor;
  d: path("M5 8h2v8H5zm7 0H9c-.55 0-1 .45-1 1v6c0 .55.45 1 1 1h3c.55 0 1-.45 1-1V9c0-.55-.45-1-1-1m-1 6h-1v-4h1zm7-6h-3c-.55 0-1 .45-1 1v6c0 .55.45 1 1 1h3c.55 0 1-.45 1-1V9c0-.55-.45-1-1-1m-1 6h-1v-4h1z");
}

</style>
