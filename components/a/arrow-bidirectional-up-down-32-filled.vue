<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iaoycdchd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-bidirectional-up-down-32-filled" /></template>
<style>
.iaoycdchd {
  fill: currentColor;
  d: path("M14.866 3.366a1.25 1.25 0 0 1 1.768 0l7 7a1.25 1.25 0 1 1-1.768 1.768L17 7.268v17.465l4.866-4.867a1.25 1.25 0 1 1 1.768 1.768l-7 7a1.25 1.25 0 0 1-1.768 0l-7-7a1.25 1.25 0 1 1 1.768-1.768l4.866 4.867V7.268l-4.866 4.866a1.25 1.25 0 1 1-1.768-1.768z");
}

</style>
