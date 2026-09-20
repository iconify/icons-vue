<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="pojefpbfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:cell-signal-none-bold" /></template>
<style>
.pojefpbfh {
  fill: currentColor;
  d: path("M52 192v8a12 12 0 0 1-24 0v-8a12 12 0 0 1 24 0");
}

</style>
