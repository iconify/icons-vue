<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvuwkucqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-timer" /></template>
<style>
.gvuwkucqj {
  fill: currentColor;
  d: path("M9 1h6v2H9zm10.03 6.39l1.42-1.42c-.43-.51-.9-.99-1.41-1.41l-1.42 1.42A8.96 8.96 0 0 0 12 4a9 9 0 0 0-9 9c0 4.97 4.02 9 9 9a8.994 8.994 0 0 0 7.03-14.61M13 14h-2V8h2z");
}

</style>
