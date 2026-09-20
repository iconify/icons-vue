<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="erv5e199t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-curve-down-left-28-filled" /></template>
<style>
.erv5e199t {
  fill: currentColor;
  d: path("M19.868 3.504a1 1 0 0 1-.372 1.364C15.138 7.36 15 11.476 15 15v7.086l4.293-4.293a1 1 0 1 1 1.414 1.414l-6 6a1 1 0 0 1-1.414 0l-6-6a1 1 0 1 1 1.414-1.414L13 22.086V15c0-3.475.063-8.759 5.504-11.868a1 1 0 0 1 1.364.372");
}

</style>
