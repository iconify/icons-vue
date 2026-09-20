<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ur2kkdbyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrows-horizontal-fill" /></template>
<style>
.ur2kkdbyp {
  fill: currentColor;
  d: path("m237.66 133.66l-32 32A8 8 0 0 1 192 160v-24H64v24a8 8 0 0 1-13.66 5.66l-32-32a8 8 0 0 1 0-11.32l32-32A8 8 0 0 1 64 96v24h128V96a8 8 0 0 1 13.66-5.66l32 32a8 8 0 0 1 0 11.32");
}

</style>
