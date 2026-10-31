<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ryoocbcwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:home-checkmark-48-filled" /></template>
<style>
.ryoocbcwm {
  fill: currentColor;
  d: path("M21.606 5.855a3.78 3.78 0 0 1 4.788 0l13.174 10.742A3.91 3.91 0 0 1 41 19.63v19.485C41 41.26 39.287 43 37.175 43h-26.35C8.713 43 7 41.26 7 39.114V19.629a3.91 3.91 0 0 1 1.432-3.032zm10.028 15.762a1.25 1.25 0 0 0-1.768 0L21.5 29.983l-3.366-3.366a1.25 1.25 0 0 0-1.768 1.767l4.25 4.25a1.25 1.25 0 0 0 1.768 0l9.25-9.25a1.25 1.25 0 0 0 0-1.767");
}

</style>
