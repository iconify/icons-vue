<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y88lm3bid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:comment-48-filled" /></template>
<style>
.y88lm3bid {
  fill: currentColor;
  d: path("M4 13.25A7.25 7.25 0 0 1 11.25 6h25.5A7.25 7.25 0 0 1 44 13.25v15.5A7.25 7.25 0 0 1 36.75 36H26.397l-10.85 7.658C14.058 44.71 12 43.644 12 41.82V36h-.75A7.25 7.25 0 0 1 4 28.75z");
}

</style>
