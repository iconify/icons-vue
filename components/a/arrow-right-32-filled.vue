<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q6c11_b_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-right-32-filled" /></template>
<style>
.q6c11_b_g {
  fill: currentColor;
  d: path("M3 16c0-.69.56-1.25 1.25-1.25h20.537l-7.432-7.628a1.25 1.25 0 1 1 1.79-1.744l9.497 9.747a1.246 1.246 0 0 1 0 1.75l-9.497 9.747a1.25 1.25 0 1 1-1.79-1.744l7.432-7.628H4.25C3.56 17.25 3 16.69 3 16");
}

</style>
