<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="ft5dv1b6b"><path class="s4v1yf91a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:block-20-filled" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.s4v1yf91a {
  d: path("M10 2a8 8 0 1 1 0 16a8 8 0 0 1 0-16zm3.5 7.5h-7l-.09.008a.5.5 0 0 0 .09.992h7l.09-.008a.5.5 0 0 0-.09-.992z");
  fill: currentColor;
}

</style>
