<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="yirx2bbib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-fat-lines-up-thin" /></template>
<style>
.yirx2bbib {
  fill: currentColor;
  d: path("m226.83 117.17l-96-96a4 4 0 0 0-5.66 0l-96 96A4 4 0 0 0 32 124h44v28a4 4 0 0 0 4 4h96a4 4 0 0 0 4-4v-28h44a4 4 0 0 0 2.83-6.83M176 116a4 4 0 0 0-4 4v28H84v-28a4 4 0 0 0-4-4H41.66L128 29.66L214.34 116Zm4 100a4 4 0 0 1-4 4H80a4 4 0 0 1 0-8h96a4 4 0 0 1 4 4m0-32a4 4 0 0 1-4 4H80a4 4 0 0 1 0-8h96a4 4 0 0 1 4 4");
}

</style>
