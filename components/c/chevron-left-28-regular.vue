<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="b17082opm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-left-28-regular" /></template>
<style>
.b17082opm {
  fill: currentColor;
  d: path("M18.03 22.78a.75.75 0 0 1-1.06 0l-8.75-8.75a.75.75 0 0 1 0-1.06l8.75-8.75a.75.75 0 1 1 1.06 1.06L9.81 13.5l8.22 8.22a.75.75 0 0 1 0 1.06");
}

</style>
