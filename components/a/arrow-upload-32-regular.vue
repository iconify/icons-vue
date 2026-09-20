<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vlx079bdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-upload-32-regular" /></template>
<style>
.vlx079bdg {
  fill: currentColor;
  d: path("M7 2a1 1 0 0 0 0 2h18a1 1 0 1 0 0-2zm9.707 4.293a1 1 0 0 0-1.414 0l-7 7a1 1 0 1 0 1.414 1.414L15 9.414V29a1 1 0 1 0 2 0V9.414l5.293 5.293a1 1 0 0 0 1.414-1.414z");
}

</style>
