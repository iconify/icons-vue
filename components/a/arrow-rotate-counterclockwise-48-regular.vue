<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iydztac8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-rotate-counterclockwise-48-regular" /></template>
<style>
.iydztac8d {
  fill: currentColor;
  d: path("M24 6c9.941 0 18 8.059 18 18a1.25 1.25 0 1 1-2.5 0c0-8.56-6.94-15.5-15.5-15.5S8.5 15.44 8.5 24c0 5.84 3.23 10.924 8 13.566V32.25a1.25 1.25 0 1 1 2.5 0v8.5c0 .69-.56 1.25-1.25 1.25h-8.5a1.25 1.25 0 1 1 0-2.5h5.599C9.553 36.367 6 30.6 6 24c0-9.941 8.059-18 18-18m0 12a6 6 0 1 1 0 12a6 6 0 0 1 0-12m0 2.5a3.5 3.5 0 1 0 0 7a3.5 3.5 0 0 0 0-7");
}

</style>
