<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="arzt5db8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:communication-16-filled" /></template>
<style>
.arzt5db8q {
  fill: currentColor;
  d: path("M8 3.5a5.5 5.5 0 0 0-3.89 9.387a.75.75 0 1 1-1.062 1.06a7 7 0 1 1 9.904 0a.75.75 0 1 1-1.061-1.06A5.5 5.5 0 0 0 8 3.5m0 4a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3M5.25 9a2.75 2.75 0 1 1 4.696 1.943a.75.75 0 0 0 1.062 1.06a4.25 4.25 0 1 0-6.015 0a.75.75 0 1 0 1.06-1.06A2.74 2.74 0 0 1 5.25 9");
}

</style>
