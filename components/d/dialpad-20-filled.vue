<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t1nd-2bca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:dialpad-20-filled" /></template>
<style>
.t1nd-2bca {
  fill: currentColor;
  d: path("M6 5.25a1.25 1.25 0 1 0 0-2.5a1.25 1.25 0 0 0 0 2.5m0 4a1.25 1.25 0 1 0 0-2.5a1.25 1.25 0 0 0 0 2.5M7.25 12a1.25 1.25 0 1 1-2.5 0a1.25 1.25 0 0 1 2.5 0M10 5.25a1.25 1.25 0 1 0 0-2.5a1.25 1.25 0 0 0 0 2.5M11.25 8a1.25 1.25 0 1 1-2.5 0a1.25 1.25 0 0 1 2.5 0M10 13.25a1.25 1.25 0 1 0 0-2.5a1.25 1.25 0 0 0 0 2.5M11.25 16a1.25 1.25 0 1 1-2.5 0a1.25 1.25 0 0 1 2.5 0M14 5.25a1.25 1.25 0 1 0 0-2.5a1.25 1.25 0 0 0 0 2.5M15.25 8a1.25 1.25 0 1 1-2.5 0a1.25 1.25 0 0 1 2.5 0M14 13.25a1.25 1.25 0 1 0 0-2.5a1.25 1.25 0 0 0 0 2.5");
}

</style>
