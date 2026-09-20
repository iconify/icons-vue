<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g28s2zb-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:alert-32-filled" /></template>
<style>
.g28s2zb-w {
  fill: currentColor;
  d: path("M7 13a9 9 0 0 1 18 0v3.807l1.928 4.822A1 1 0 0 1 26 23H6a1 1 0 0 1-.928-1.371L7 16.807zm5.125 12A3.99 3.99 0 0 0 16 28a3.99 3.99 0 0 0 3.875-3z");
}

</style>
