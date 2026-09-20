<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bglwzdb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-download-32-filled" /></template>
<style>
.bglwzdb4g {
  fill: currentColor;
  d: path("M17.25 4.25a1.25 1.25 0 1 0-2.5 0v15.482l-4.616-4.616a1.25 1.25 0 0 0-1.768 1.768l6.75 6.75a1.25 1.25 0 0 0 1.768 0l6.75-6.75a1.25 1.25 0 0 0-1.768-1.768l-4.616 4.616zm-11 22.25a1.25 1.25 0 1 0 0 2.5h19.5a1.25 1.25 0 1 0 0-2.5z");
}

</style>
