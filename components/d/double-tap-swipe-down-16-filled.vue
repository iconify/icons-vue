<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="iij_habzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:double-tap-swipe-down-16-filled" /></template>
<style>
.iij_habzy {
  fill: currentColor;
  d: path("M4 5.5a4 4 0 1 1 5.75 3.598v1.618A5.502 5.502 0 0 0 8 0a5.5 5.5 0 0 0-1.75 10.716V9.098A4 4 0 0 1 4 5.5m7 0a3 3 0 0 1-1.25 2.437V5.75a1.75 1.75 0 1 0-3.5 0v2.187A3 3 0 1 1 11 5.5m-2.25.25a.75.75 0 0 0-1.5 0v7.19l-1.22-1.22a.75.75 0 0 0-1.06 1.06l2.5 2.5a.75.75 0 0 0 1.06 0l2.5-2.5a.75.75 0 1 0-1.06-1.06l-1.22 1.22z");
}

</style>
