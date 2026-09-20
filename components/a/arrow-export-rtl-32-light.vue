<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gdgul0ifl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-export-rtl-32-light" /></template>
<style>
.gdgul0ifl {
  fill: currentColor;
  d: path("M29.5 5a.5.5 0 0 1 .5.5v20a.5.5 0 0 1-1 0v-20a.5.5 0 0 1 .5-.5M10.146 7.146a.5.5 0 0 1 .707.708L3.708 15H25.5a.5.5 0 0 1 0 1H3.707l7.147 7.147a.5.5 0 0 1-.708.707l-8-8a.5.5 0 0 1 0-.707z");
}

</style>
