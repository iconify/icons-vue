<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xh2k4rb5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:line-horizontal-4-search-32-light" /></template>
<style>
.xh2k4rb5b {
  fill: currentColor;
  d: path("M29.5 26a.5.5 0 0 1 0 1h-27a.5.5 0 0 1 0-1zM19 2a7 7 0 0 1 5.29 11.582l6.564 6.564a.5.5 0 1 1-.707.707l-6.565-6.564A7 7 0 1 1 19 2m8.172 18H2.5a.5.5 0 0 1 0-1h23.672zM19 3a6 6 0 1 0 0 12a6 6 0 0 0 0-12m-7.954 9q.196.517.454 1h-9a.5.5 0 0 1 0-1zm.454-7a9 9 0 0 0-.454 1H2.5a.5.5 0 0 1 0-1z");
}

</style>
