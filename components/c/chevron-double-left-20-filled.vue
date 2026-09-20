<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kjfi3abeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-double-left-20-filled" /></template>
<style>
.kjfi3abeo {
  fill: currentColor;
  d: path("M8.97 4.22a.75.75 0 1 1 1.06 1.06L5.31 10l4.72 4.72a.75.75 0 1 1-1.06 1.06l-5.25-5.25a.75.75 0 0 1 0-1.06zm5.5 0a.75.75 0 1 1 1.06 1.06L10.81 10l4.72 4.72a.75.75 0 1 1-1.06 1.06l-5.25-5.25a.75.75 0 0 1 0-1.06z");
}

</style>
