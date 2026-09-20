<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qgqtrnbru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-up-16-filled" /></template>
<style>
.qgqtrnbru {
  fill: currentColor;
  d: path("M8 14a.75.75 0 0 1-.75-.75V4.463L4.309 7.75a.75.75 0 0 1-1.118-1L7.441 2A.75.75 0 0 1 8.56 2l4.25 4.75a.75.75 0 1 1-1.118 1L8.75 4.463v8.787A.75.75 0 0 1 8 14");
}

</style>
