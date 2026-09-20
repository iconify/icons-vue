<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="kqspalbsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:dialpad-28-regular" /></template>
<style>
.kqspalbsl {
  fill: currentColor;
  d: path("M9 4.5a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0m0 6a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0m0 6a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0m6.5-12a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0m0 6a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0m0 6a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0m0 6a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0m6.5-18a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0m0 6a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0m0 6a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0");
}

</style>
