<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="pwor2rgew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-circle-down-right-light" /></template>
<style>
.pwor2rgew {
  fill: currentColor;
  d: path("M128 26a102 102 0 1 0 102 102A102.12 102.12 0 0 0 128 26m0 192a90 90 0 1 1 90-90a90.1 90.1 0 0 1-90 90m38-106v48a6 6 0 0 1-6 6h-48a6 6 0 0 1 0-12h33.51l-53.75-53.76a6 6 0 0 1 8.48-8.48L154 145.51V112a6 6 0 0 1 12 0");
}

</style>
