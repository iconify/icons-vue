<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a-q-spb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:dismiss-48-regular" /></template>
<style>
.a-q-spb7w {
  fill: currentColor;
  d: path("M8.384 6.616a1.25 1.25 0 1 0-1.768 1.768L22.232 24L6.616 39.616a1.25 1.25 0 0 0 1.768 1.768L24 25.768l15.615 15.615a1.25 1.25 0 1 0 1.768-1.768L25.768 24L41.383 8.384a1.25 1.25 0 1 0-1.767-1.767L24 22.232z");
}

</style>
