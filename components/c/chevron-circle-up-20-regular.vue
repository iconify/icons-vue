<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xgn_xbcik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-circle-up-20-regular" /></template>
<style>
.xgn_xbcik {
  fill: currentColor;
  d: path("M3 10a7 7 0 1 0 14 0a7 7 0 0 0-14 0m7 8a8 8 0 1 1 0-16a8 8 0 0 1 0 16m-3.146-6.146a.5.5 0 0 1-.708-.708l3.5-3.5a.5.5 0 0 1 .708 0l3.5 3.5a.5.5 0 0 1-.708.708L10 8.707z");
}

</style>
