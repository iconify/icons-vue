<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="y5vvt6kfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:circle-image-20-regular" /></template>
<style>
.y5vvt6kfg {
  fill: currentColor;
  d: path("M15.5 8a2.5 2.5 0 0 1 2.5 2.5v5a2.5 2.5 0 0 1-2.5 2.5h-5A2.5 2.5 0 0 1 8 15.5v-5A2.5 2.5 0 0 1 10.5 8zm-1.793 6.414a1 1 0 0 0-1.414 0l-2.44 2.44c.196.093.415.146.647.146h5a1.5 1.5 0 0 0 .646-.146zM10.5 9A1.5 1.5 0 0 0 9 10.5v5c0 .232.053.45.146.646l2.44-2.439a2 2 0 0 1 2.828 0l2.44 2.44c.093-.196.146-.415.146-.647v-5A1.5 1.5 0 0 0 15.5 9zM8 2a6 6 0 0 1 5.915 5h-1.016A5.001 5.001 0 1 0 7 12.9v1.015A6 6 0 0 1 8 2m7 8a1 1 0 1 1 0 2a1 1 0 0 1 0-2");
}

</style>
