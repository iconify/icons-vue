<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w2ibj_b2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-previous-16-filled" /></template>
<style>
.w2ibj_b2f {
  fill: currentColor;
  d: path("M12.296 11.736a.75.75 0 1 1-1.092 1.028l-4-4.25a.75.75 0 0 1 0-1.027l4-4.25a.75.75 0 1 1 1.092 1.028L8.78 8zM4.75 3a.75.75 0 0 0-.75.75v8.5a.75.75 0 0 0 1.5 0v-8.5A.75.75 0 0 0 4.75 3");
}

</style>
