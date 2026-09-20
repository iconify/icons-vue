<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="avnbuw1mf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-square-32-regular" /></template>
<style>
.avnbuw1mf {
  fill: currentColor;
  d: path("M19.068 3a3.25 3.25 0 0 1 2.298.952l6.682 6.682c.61.61.952 1.436.952 2.298V25.75A3.25 3.25 0 0 1 25.75 29H6.25A3.25 3.25 0 0 1 3 25.75V6.25A3.25 3.25 0 0 1 6.25 3zM6.25 5C5.56 5 5 5.56 5 6.25v19.5c0 .69.56 1.25 1.25 1.25h19.5c.69 0 1.25-.56 1.25-1.25V14h-5.75A3.25 3.25 0 0 1 18 10.75V5zM20 10.75c0 .69.56 1.25 1.25 1.25h5.336L20 5.414z");
}

</style>
