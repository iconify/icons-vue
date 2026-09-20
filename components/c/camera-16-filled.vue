<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n1hq6nmue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:camera-16-filled" /></template>
<style>
.n1hq6nmue {
  fill: currentColor;
  d: path("M10 8a2 2 0 1 1-4 0a2 2 0 0 1 4 0M5.276 2.83A1.5 1.5 0 0 1 6.618 2h2.764a1.5 1.5 0 0 1 1.342.83L11.309 4H12a2 2 0 0 1 2 2v5a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h.691zM11 8a3 3 0 1 0-6 0a3 3 0 0 0 6 0");
}

</style>
