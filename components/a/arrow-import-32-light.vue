<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rzi8hdc5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-import-32-light" /></template>
<style>
.rzi8hdc5o {
  fill: currentColor;
  d: path("M29.5 5a.5.5 0 0 1 .5.5v20a.5.5 0 0 1-1 0v-20a.5.5 0 0 1 .5-.5M17.147 7.146a.5.5 0 0 1 .707 0l8 8a.5.5 0 0 1 0 .707l-8 8a.5.5 0 1 1-.707-.707L24.293 16H2.5a.5.5 0 0 1 0-1h21.793l-7.146-7.146a.5.5 0 0 1 0-.708");
}

</style>
