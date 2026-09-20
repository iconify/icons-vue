<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="pyrak7i_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-right-28-filled" /></template>
<style>
.pyrak7i_g {
  fill: currentColor;
  d: path("M9.543 4.293a1 1 0 0 1 1.414 0l8.75 8.75a1 1 0 0 1 0 1.414l-8.75 8.75a1 1 0 0 1-1.414-1.414l8.043-8.043l-8.043-8.043a1 1 0 0 1 0-1.414");
}

</style>
