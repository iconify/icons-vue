<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b7yifacwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:link-32-light" /></template>
<style>
.b7yifacwk {
  fill: currentColor;
  d: path("M2 15.5A6.5 6.5 0 0 1 8.5 9h5a.5.5 0 0 1 0 1h-5a5.5 5.5 0 1 0 0 11h5a.5.5 0 0 1 0 1h-5A6.5 6.5 0 0 1 2 15.5m28 0A6.5 6.5 0 0 0 23.5 9h-5a.5.5 0 0 0 0 1h5a5.5 5.5 0 1 1 0 11h-5a.5.5 0 0 0 0 1h5a6.5 6.5 0 0 0 6.5-6.5M9.5 15a.5.5 0 0 0 0 1h13a.5.5 0 0 0 0-1z");
}

</style>
