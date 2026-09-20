<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yqz21gbto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:dismiss-square-32-light" /></template>
<style>
.yqz21gbto {
  fill: currentColor;
  d: path("M24.5 3A4.5 4.5 0 0 1 29 7.5v17a4.5 4.5 0 0 1-4.5 4.5h-17A4.5 4.5 0 0 1 3 24.5v-17A4.5 4.5 0 0 1 7.5 3zm-17 1A3.5 3.5 0 0 0 4 7.5v17A3.5 3.5 0 0 0 7.5 28h17a3.5 3.5 0 0 0 3.5-3.5v-17A3.5 3.5 0 0 0 24.5 4zm13.647 6.147a.5.5 0 1 1 .707.707L16.707 16l5.147 5.147a.5.5 0 1 1-.707.707L16 16.707l-5.146 5.147a.5.5 0 1 1-.707-.707L15.293 16l-5.146-5.146a.5.5 0 1 1 .707-.707L16 15.293z");
}

</style>
