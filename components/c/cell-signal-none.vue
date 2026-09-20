<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="r8fxz-3nj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:cell-signal-none" /></template>
<style>
.r8fxz-3nj {
  fill: currentColor;
  d: path("M48 192v8a8 8 0 0 1-16 0v-8a8 8 0 0 1 16 0");
}

</style>
