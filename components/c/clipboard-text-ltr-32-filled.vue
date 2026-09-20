<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ibbg6df3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:clipboard-text-ltr-32-filled" /></template>
<style>
.ibbg6df3s {
  fill: currentColor;
  d: path("M21.83 4h1.67A3.5 3.5 0 0 1 27 7.5v19a3.5 3.5 0 0 1-3.5 3.5h-15A3.5 3.5 0 0 1 5 26.5v-19A3.5 3.5 0 0 1 8.5 4h1.67A3 3 0 0 1 13 2h6c1.306 0 2.418.835 2.83 2M19 4h-6a1 1 0 1 0 0 2h6a1 1 0 1 0 0-2m-8 8a1 1 0 1 0 0 2h10a1 1 0 1 0 0-2zm-1 6a1 1 0 0 0 1 1h5a1 1 0 1 0 0-2h-5a1 1 0 0 0-1 1m1 4a1 1 0 1 0 0 2h8a1 1 0 1 0 0-2z");
}

</style>
