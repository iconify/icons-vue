<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ixmk6jr_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-rotate-counterclockwise-32-regular" /></template>
<style>
.ixmk6jr_h {
  fill: currentColor;
  d: path("M16 3c7.18 0 13 5.82 13 13a1 1 0 1 1-2 0c0-6.075-4.925-11-11-11S5 9.925 5 16c0 3.86 1.99 7.253 5 9.215V22a1 1 0 1 1 2 0v6a1 1 0 0 1-1 1H5a1 1 0 1 1 0-2h4.074C5.425 24.698 3 20.633 3 16C3 8.82 8.82 3 16 3m0 9a4 4 0 1 1 0 8a4 4 0 0 1 0-8m0 2a2 2 0 1 0 0 4a2 2 0 0 0 0-4");
}

</style>
