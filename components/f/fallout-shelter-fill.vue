<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="u4i7gdy1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:fallout-shelter-fill" /></template>
<style>
.u4i7gdy1n {
  fill: currentColor;
  d: path("M231.94 124.55c-1.77-54.49-46-98.72-100.49-100.49A104.09 104.09 0 0 0 24.06 131.45c1.77 54.49 46 98.72 100.49 100.49a104.09 104.09 0 0 0 107.39-107.39m-33.56 16.92l-23.45 32.83a8.52 8.52 0 0 1-13.86 0L128 128l-33.07 46.3a8.52 8.52 0 0 1-13.86 0l-23.45-32.83A8.52 8.52 0 0 1 64.55 128H128L97.62 85.47A8.52 8.52 0 0 1 104.55 72h46.9a8.52 8.52 0 0 1 6.93 13.47L128 128h63.45a8.52 8.52 0 0 1 6.93 13.47");
}

</style>
