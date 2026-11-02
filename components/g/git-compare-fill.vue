<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ft8p6yb8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-compare-fill" /></template>
<style>
.ft8p6yb8y {
  fill: currentColor;
  d: path("M17 5a3 3 0 0 1 3 3v7.171a3 3 0 1 1-2 0V8a1 1 0 0 0-1-1h-3.586l1.293 1.293a.999.999 0 1 1-1.414 1.414l-3-3a1 1 0 0 1 0-1.414l3-3a.999.999 0 1 1 1.414 1.414L13.414 5ZM6 8.829V16a1 1 0 0 0 1 1h3.586l-1.293-1.293a.999.999 0 1 1 1.414-1.414l3 3a1 1 0 0 1 0 1.414l-3 3a.999.999 0 1 1-1.414-1.414L10.586 19H7a3 3 0 0 1-3-3V8.829a3 3 0 1 1 2 0");
}

</style>
