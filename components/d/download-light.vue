<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="s9m5f391z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:download-light" /></template>
<style>
.s9m5f391z {
  fill: currentColor;
  d: path("M238 136v64a14 14 0 0 1-14 14H32a14 14 0 0 1-14-14v-64a14 14 0 0 1 14-14h40a6 6 0 0 1 0 12H32a2 2 0 0 0-2 2v64a2 2 0 0 0 2 2h192a2 2 0 0 0 2-2v-64a2 2 0 0 0-2-2h-40a6 6 0 0 1 0-12h40a14 14 0 0 1 14 14m-114.24-3.76a6 6 0 0 0 8.48 0l48-48a6 6 0 0 0-8.48-8.48L134 113.51V24a6 6 0 0 0-12 0v89.51L84.24 75.76a6 6 0 0 0-8.48 8.48ZM198 168a10 10 0 1 0-10 10a10 10 0 0 0 10-10");
}

</style>
