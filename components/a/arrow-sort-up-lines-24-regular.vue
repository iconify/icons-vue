<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kon5wac9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-sort-up-lines-24-regular" /></template>
<style>
.kon5wac9t {
  fill: currentColor;
  d: path("M18 21.25a.75.75 0 0 1-1.5 0V4.56l-2.22 2.22a.75.75 0 1 1-1.06-1.06l3.5-3.5a.75.75 0 0 1 1.06 0l3.5 3.5a.75.75 0 0 1-1.06 1.06L18 4.56zM2.75 19.5a.75.75 0 0 1 0-1.5h10.5a.75.75 0 0 1 0 1.5zM6 14.75c0 .414.336.75.75.75h6.5a.75.75 0 0 0 0-1.5h-6.5a.75.75 0 0 0-.75.75m4.75-3.25a.75.75 0 0 1 0-1.5h2.5a.75.75 0 0 1 0 1.5z");
}

</style>
