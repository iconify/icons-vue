<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m5avl_two"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:door-add-20-filled" /></template>
<style>
.m5avl_two {
  fill: currentColor;
  d: path("M14.5 10a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9M14 2a2 2 0 0 1 2 2v5.208A5.503 5.503 0 0 0 9 14.5c0 1.33.472 2.549 1.258 3.5H6a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2zm.5 10a.5.5 0 0 0-.5.5V14h-1.5a.5.5 0 0 0 0 1H14v1.5a.5.5 0 0 0 1 0V15h1.5a.5.5 0 0 0 0-1H15v-1.5a.5.5 0 0 0-.5-.5M7 9a1 1 0 1 0 0 2a1 1 0 0 0 0-2");
}

</style>
