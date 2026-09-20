<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="yf84oab4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:letter-x" /></template>
<style>
.yf84oab4b {
  fill: var(--svg-color--40c0e7, #40c0e7);
  d: path("M114.31 117.18L81.14 68.9l33-49.02c.48-.73.54-1.66.12-2.43a2.36 2.36 0 0 0-2.08-1.25H84.33c-.78 0-1.51.38-1.95 1.03L64 43.97L45.62 17.22a2.37 2.37 0 0 0-1.95-1.03H15.83c-.87 0-1.68.48-2.08 1.25c-.42.77-.36 1.71.12 2.43L46.86 68.9l-33.17 48.28c-.49.72-.55 1.66-.14 2.44c.41.77 1.22 1.26 2.09 1.26H44.9c.79 0 1.52-.39 1.96-1.04L64 94.36l17.15 25.48c.44.65 1.17 1.04 1.96 1.04h29.25c.88 0 1.68-.49 2.1-1.26c.4-.78.35-1.72-.15-2.44");
}

</style>
