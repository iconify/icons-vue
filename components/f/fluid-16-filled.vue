<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fxi0rvyob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:fluid-16-filled" /></template>
<style>
.fxi0rvyob {
  fill: currentColor;
  d: path("M1 2.5A1.5 1.5 0 0 1 2.5 1h2A1.5 1.5 0 0 1 6 2.5v2A1.5 1.5 0 0 1 4.5 6h-2A1.5 1.5 0 0 1 1 4.5zm7 7A1.5 1.5 0 0 1 9.5 8h4A1.5 1.5 0 0 1 15 9.5v4a1.5 1.5 0 0 1-1.5 1.5h-4A1.5 1.5 0 0 1 8 13.5zm-5 1V7h1v3.5a.5.5 0 0 0 .5.5H7v1H4.5A1.5 1.5 0 0 1 3 10.5M7 3v1h3.5a.5.5 0 0 1 .5.5V7h1V4.5A1.5 1.5 0 0 0 10.5 3z");
}

</style>
