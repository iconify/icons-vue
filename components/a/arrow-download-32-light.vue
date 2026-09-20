<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="veq0-v3th"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-download-32-light" /></template>
<style>
.veq0-v3th {
  fill: currentColor;
  d: path("M16 3a.5.5 0 0 1 .5.5v18.293l6.646-6.647a.5.5 0 0 1 .708.708l-7.5 7.5a.5.5 0 0 1-.708 0l-7.5-7.5a.5.5 0 0 1 .708-.708l6.646 6.647V3.5A.5.5 0 0 1 16 3M6.5 28.5a.5.5 0 0 1 0-1h19a.5.5 0 0 1 0 1z");
}

</style>
