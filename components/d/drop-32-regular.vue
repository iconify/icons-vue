<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tjzgocf8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:drop-32-regular" /></template>
<style>
.tjzgocf8d {
  fill: currentColor;
  d: path("M24 20c0-3.662-2.093-7.696-4.322-10.92A45 45 0 0 0 16 4.46a45 45 0 0 0-3.678 4.62C10.093 12.304 8 16.338 8 20a8 8 0 1 0 16 0m2 0c0 5.523-4.477 10-10 10S6 25.523 6 20c0-4.308 2.407-8.774 4.678-12.058a47 47 0 0 1 4.206-5.222C15.196 2.387 15.495 2 16 2c.509 0 .803.386 1.116.72a47 47 0 0 1 4.206 5.223C23.593 11.225 26 15.691 26 20");
}

</style>
