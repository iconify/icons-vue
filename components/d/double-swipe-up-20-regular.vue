<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d5jrakbrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:double-swipe-up-20-regular" /></template>
<style>
.d5jrakbrc {
  fill: currentColor;
  d: path("M5.854 2.146a.5.5 0 0 0-.708 0l-3 3a.5.5 0 1 0 .708.708L5 3.707V14.5a.5.5 0 0 0 1 0V3.707l2.146 2.147a.5.5 0 1 0 .708-.708zm9 0a.5.5 0 0 0-.708 0l-3 3a.5.5 0 0 0 .708.708L14 3.707V14.5a.5.5 0 0 0 1 0V3.707l2.146 2.147a.5.5 0 0 0 .708-.708zM11 14.5a3.5 3.5 0 0 1 2-3.163V12.5a2.5 2.5 0 1 0 3 0v-1.163a3.5 3.5 0 1 1-5 3.163m-7-3.163a3.5 3.5 0 1 0 3 0V12.5a2.5 2.5 0 1 1-3 0z");
}

</style>
