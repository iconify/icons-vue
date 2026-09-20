<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="xa73hnotr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrows-split-light" /></template>
<style>
.xa73hnotr {
  fill: currentColor;
  d: path("m228.24 188.24l-32 32a6 6 0 0 1-8.48 0l-32-32a6 6 0 0 1 8.48-8.48L186 201.51v-63l-58-58l-58 58v63l21.76-21.75a6 6 0 0 1 8.48 8.48l-32 32a6 6 0 0 1-8.48 0l-32-32a6 6 0 0 1 8.48-8.48L58 201.51V136a6 6 0 0 1 1.76-4.24L122 69.51V24a6 6 0 0 1 12 0v45.51l62.24 62.25A6 6 0 0 1 198 136v65.51l21.76-21.75a6 6 0 0 1 8.48 8.48");
}

</style>
