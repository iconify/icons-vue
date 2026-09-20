<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hc662wgqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-redo-20-regular" /></template>
<style>
.hc662wgqc {
  fill: currentColor;
  d: path("M15.003 2.5a.5.5 0 0 1 1 0v4.9a.6.6 0 0 1-.6.6h-4.9a.5.5 0 0 1 0-1h3.594l-3.473-3.019a4 4 0 1 0-5.248 6.038l8.172 7.104a.5.5 0 1 1-.656.754L4.72 10.774a5 5 0 1 1 6.56-7.547l3.723 3.236z");
}

</style>
