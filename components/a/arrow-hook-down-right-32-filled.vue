<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nd-jhuj5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-hook-down-right-32-filled" /></template>
<style>
.nd-jhuj5y {
  fill: currentColor;
  d: path("M22 7a1.25 1.25 0 1 1 0 2.5h-8.75a4.75 4.75 0 1 0 0 9.5h8.482l-2.866-2.866a1.25 1.25 0 0 1 1.768-1.768l5 5a1.25 1.25 0 0 1 0 1.768l-5 5l-.095.086a1.25 1.25 0 0 1-1.759-1.76l.086-.094l2.866-2.866H13.25a7.25 7.25 0 1 1 0-14.5z");
}

</style>
