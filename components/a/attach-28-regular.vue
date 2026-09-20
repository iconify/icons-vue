<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="c5je6ib5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:attach-28-regular" /></template>
<style>
.c5je6ib5m {
  fill: currentColor;
  d: path("M22.456 5.042a5.26 5.26 0 0 0-7.437 0L3.276 16.78a.75.75 0 0 1-1.06-1.06l11.74-11.74a6.76 6.76 0 1 1 9.558 9.563l-11.32 11.31a3.928 3.928 0 0 1-5.554-5.556L17.717 8.22a.75.75 0 1 1 1.06 1.06L7.703 20.358a2.428 2.428 0 0 0 3.433 3.434l11.32-11.31a5.26 5.26 0 0 0 .001-7.44");
}

</style>
