<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="cj1hd1btd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:cell-signal-full" /></template>
<style>
.cj1hd1btd {
  fill: currentColor;
  d: path("M168 72v128a8 8 0 0 1-16 0V72a8 8 0 0 1 16 0m32-48a8 8 0 0 0-8 8v168a8 8 0 0 0 16 0V32a8 8 0 0 0-8-8m-80 80a8 8 0 0 0-8 8v88a8 8 0 0 0 16 0v-88a8 8 0 0 0-8-8m-40 40a8 8 0 0 0-8 8v48a8 8 0 0 0 16 0v-48a8 8 0 0 0-8-8m-40 40a8 8 0 0 0-8 8v8a8 8 0 0 0 16 0v-8a8 8 0 0 0-8-8");
}

</style>
