<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ylbqn9bfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:dock-right-20-filled" /></template>
<style>
.ylbqn9bfi {
  fill: currentColor;
  d: path("M15 3a3 3 0 0 1 3 3v7a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3zM5 4a2 2 0 0 0-2 2v7a2 2 0 0 0 2 2h6.5V4z");
}

</style>
