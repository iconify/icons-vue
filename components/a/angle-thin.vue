<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="wtkbyqb0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:angle-thin" /></template>
<style>
.wtkbyqb0o {
  fill: currentColor;
  d: path("M100 72a4 4 0 0 1 4-4a100.11 100.11 0 0 1 100 100a4 4 0 0 1-8 0a92.1 92.1 0 0 0-92-92a4 4 0 0 1-4-4m140 124H76V32a4 4 0 0 0-8 0v36H32a4 4 0 0 0 0 8h36v124a4 4 0 0 0 4 4h168a4 4 0 0 0 0-8");
}

</style>
