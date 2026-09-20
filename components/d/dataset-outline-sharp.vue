<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwv1xl1lq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:dataset-outline-sharp" /></template>
<style>
.qwv1xl1lq {
  fill: currentColor;
  d: path("M4 20V4h16v16zm1-1h14V5H5zm0 0V5zm2.5-8.5h3v-3h-3zm6 0h3v-3h-3zm-6 6h3v-3h-3zm6 0h3v-3h-3z");
}

</style>
