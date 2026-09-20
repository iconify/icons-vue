<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xa3pr8b6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:door-32-regular" /></template>
<style>
.xa3pr8b6r {
  fill: currentColor;
  d: path("M23.75 2A3.25 3.25 0 0 1 27 5.25v21.5A3.25 3.25 0 0 1 23.75 30H8.25a3.25 3.25 0 0 1-3.246-3.083L5 26.75V5.25A3.25 3.25 0 0 1 8.25 2zM8.25 4C7.56 4 7 4.56 7 5.25v21.5l.007.128A1.25 1.25 0 0 0 8.25 28h15.5c.69 0 1.25-.56 1.25-1.25V5.25C25 4.56 24.44 4 23.75 4zm2.25 9.75a1.75 1.75 0 1 1 0 3.5a1.75 1.75 0 0 1 0-3.5");
}

</style>
