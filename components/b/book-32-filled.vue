<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r6ok76brd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:book-32-filled" /></template>
<style>
.r6ok76brd {
  fill: currentColor;
  d: path("M5 26V6a4 4 0 0 1 4-4h14a4 4 0 0 1 4 4v18.25A1.75 1.75 0 0 1 25.25 26H7a2 2 0 0 0 2 2h17a1 1 0 1 1 0 2H9a4 4 0 0 1-4-4m5.75-20A1.75 1.75 0 0 0 9 7.75v1.5c0 .966.784 1.75 1.75 1.75h10.5A1.75 1.75 0 0 0 23 9.25v-1.5A1.75 1.75 0 0 0 21.25 6z");
}

</style>
