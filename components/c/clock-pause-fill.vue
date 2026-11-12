<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yp0eamxxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clock-pause-fill" /></template>
<style>
.yp0eamxxl {
  fill: currentColor;
  d: path("M18 11a7 7 0 0 0-5.612-6.861A7 7 0 0 0 4.55 8.276a6.99 6.99 0 0 0 1.5 7.674A6.97 6.97 0 0 0 11 18a1 1 0 0 1 0 2A9 9 0 0 1 6.028 3.498a9 9 0 0 1 8.476-.79A8.99 8.99 0 0 1 20 11a1 1 0 0 1-2 0m-6-4v3h2a1 1 0 0 1 0 2h-3a1 1 0 0 1-1-1V7a1 1 0 0 1 2 0m3 14v-6a1 1 0 0 1 2 0v6a1 1 0 0 1-2 0m4 0v-6a1 1 0 0 1 2 0v6a1 1 0 0 1-2 0");
}

</style>
