<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="knqhrbubw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-next-16-filled" /></template>
<style>
.knqhrbubw {
  fill: currentColor;
  d: path("M3.704 11.736a.75.75 0 1 0 1.092 1.028l4-4.25a.75.75 0 0 0 0-1.027l-4-4.25a.75.75 0 1 0-1.092 1.028L7.22 8zM11.25 3a.75.75 0 0 1 .75.75v8.5a.75.75 0 0 1-1.5 0v-8.5a.75.75 0 0 1 .75-.75");
}

</style>
