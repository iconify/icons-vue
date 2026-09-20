<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kw83gyb8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:hexagon-32-filled" /></template>
<style>
.kw83gyb8n {
  fill: currentColor;
  d: path("M10.617 3a3 3 0 0 0-2.559 1.433l-6.123 10a3 3 0 0 0 0 3.134l6.123 10A3 3 0 0 0 10.617 29h10.758a3 3 0 0 0 2.56-1.434l6.119-10a3 3 0 0 0 0-3.132l-6.12-10A3 3 0 0 0 21.375 3z");
}

</style>
