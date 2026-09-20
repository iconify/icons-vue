<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n551uj5sb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:diamond-link-16-regular" /></template>
<style>
.n551uj5sb {
  fill: currentColor;
  d: path("M6.822 4.282a5.536 5.536 0 0 1 3.31 9.415l-.717.718a2 2 0 0 1-2.83.001l-5-5a2 2 0 0 1 0-2.83l.72-.717a5.6 5.6 0 0 1 1.046-.822a6.6 6.6 0 0 0-.103 1.31q-.121.106-.236.22l-.72.717a1 1 0 0 0 0 1.414l5 5.001c.391.39 1.026.39 1.416 0l.717-.72A4.536 4.536 0 0 0 6.38 5.251c.096-.338.243-.666.442-.969m-.235-2.696a2 2 0 0 1 2.829 0l5 4.998a2 2 0 0 1-.002 2.83l-.719.72a5.6 5.6 0 0 1-1.048.82a6.6 6.6 0 0 0 .104-1.31q.12-.103.237-.217l.72-.72a1 1 0 0 0 0-1.415l-5-5a1 1 0 0 0-1.414 0l-.72.72a4.536 4.536 0 0 0 3.045 7.74a3.5 3.5 0 0 1-.442.969a5.536 5.536 0 0 1-3.31-9.415z");
}

</style>
