<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f9v74lbns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:gauge-rotate-315-24-filled" /></template>
<style>
.f9v74lbns {
  fill: currentColor;
  d: path("M13.11 2.061c5.001.553 8.89 4.792 8.89 9.94c0 5.522-4.477 10-10 10S2 17.523 2 12a9.98 9.98 0 0 1 3.083-7.223a1 1 0 0 1 1.384 1.444A8 8 0 1 0 12.89 4.05a1 1 0 0 1 .22-1.988m-6.223 5.8c-.259-.603.371-1.233.974-.975l.13.07c1.637 1.083 3.285 2.154 4.884 3.293c.404.288.745.543.89.688a2 2 0 1 1-2.828 2.828c-.145-.145-.4-.486-.688-.89c-.902-1.267-2.427-3.568-3.293-4.884z");
}

</style>
