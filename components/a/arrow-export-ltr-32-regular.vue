<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y2u0pbbkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-export-ltr-32-regular" /></template>
<style>
.y2u0pbbkx {
  fill: currentColor;
  d: path("M3 5a1 1 0 0 1 1 1v20a1 1 0 1 1-2 0V6a1 1 0 0 1 1-1m17.793 2.793a1 1 0 0 1 1.414 0l7.5 7.5a1 1 0 0 1 0 1.414l-7.5 7.5a1 1 0 1 1-1.414-1.414L26.586 17H8a1 1 0 1 1 0-2h18.586l-5.793-5.793a1 1 0 0 1 0-1.414");
}

</style>
