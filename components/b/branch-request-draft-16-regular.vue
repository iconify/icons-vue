<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c0e58lauk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:branch-request-draft-16-regular" /></template>
<style>
.c0e58lauk {
  fill: currentColor;
  d: path("M2 3.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 0 0-3 0m4 0a2.5 2.5 0 0 1-2 2.45v4.1a2.5 2.5 0 1 1-1 0v-4.1A2.5 2.5 0 1 1 6 3.5m-4 9a1.5 1.5 0 1 0 3 0a1.5 1.5 0 0 0-3 0m9 0a1.5 1.5 0 1 1 3 0a1.5 1.5 0 0 1-3 0m1.5-2.5a2.5 2.5 0 1 0 0 5a2.5 2.5 0 0 0 0-5m1-3a1 1 0 1 1-2 0a1 1 0 0 1 2 0m-1-3a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

</style>
