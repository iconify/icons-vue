<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="nusn7mdqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:less-than-or-equal-thin" /></template>
<style>
.nusn7mdqi {
  fill: currentColor;
  d: path("M44 104a4 4 0 0 1 2.62-3.75l152-56a4 4 0 1 1 2.76 7.5L59.57 104l141.81 52.25A4 4 0 0 1 200 164a3.9 3.9 0 0 1-1.38-.25l-152-56A4 4 0 0 1 44 104m156 92H48a4 4 0 0 0 0 8h152a4 4 0 0 0 0-8");
}

</style>
