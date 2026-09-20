<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="walo6863q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:font-download-outline-sharp" /></template>
<style>
.walo6863q {
  fill: currentColor;
  d: path("M7.439 17.577H8.5l1.062-3.011h4.877l1.061 3.011h1.062L12.433 6.192h-.868zm2.453-3.954l2.058-5.796h.1l2.058 5.796zM3 21V3h18v18zm1-1h16V4H4zm0 0V4z");
}

</style>
