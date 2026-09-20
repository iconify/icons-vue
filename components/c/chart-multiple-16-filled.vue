<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c-qz9kbob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chart-multiple-16-filled" /></template>
<style>
.c-qz9kbob {
  fill: currentColor;
  d: path("M12 7c0-.684.343-1.287.866-1.648A5.574 5.574 0 0 0 7.43 1a.436.436 0 0 0-.43.445V6.5a.5.5 0 0 0 .5.5zM1 7.5a5.5 5.5 0 0 0 5 5.478V11a2 2 0 0 1 3-1.732V9c0-.364.097-.706.268-1H7a1 1 0 0 1-1-1V2.571c0-.294-.253-.526-.542-.47A5.5 5.5 0 0 0 1 7.5M14 6a1 1 0 0 0-1 1v7a1 1 0 1 0 2 0V7a1 1 0 0 0-1-1m-3 2a1 1 0 0 0-1 1v5a1 1 0 1 0 2 0V9a1 1 0 0 0-1-1m-4 3a1 1 0 1 1 2 0v3a1 1 0 1 1-2 0z");
}

</style>
