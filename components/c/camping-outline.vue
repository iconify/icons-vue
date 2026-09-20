<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wn_8-16ds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:camping-outline" /></template>
<style>
.wn_8-16ds {
  fill: currentColor;
  d: path("M2 22v-4.65l8.75-11.8L9 3.2L10.6 2L12 3.875L13.4 2L15 3.2l-1.75 2.35L22 17.35V22zM12 7.225L4 18v2h3l5-7l5 7h3v-2zM9.45 20h5.1L12 16.45zM12 13l5 7zl-5 7z");
}

</style>
