<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="q1n72l43p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:command-light" /></template>
<style>
.q1n72l43p {
  fill: currentColor;
  d: path("M180 146h-22v-36h22a34 34 0 1 0-34-34v22h-36V76a34 34 0 1 0-34 34h22v36H76a34 34 0 1 0 34 34v-22h36v22a34 34 0 1 0 34-34m-22-70a22 22 0 1 1 22 22h-22ZM54 76a22 22 0 0 1 44 0v22H76a22 22 0 0 1-22-22m44 104a22 22 0 1 1-22-22h22Zm12-70h36v36h-36Zm70 92a22 22 0 0 1-22-22v-22h22a22 22 0 0 1 0 44");
}

</style>
