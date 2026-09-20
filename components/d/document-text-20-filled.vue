<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="obkkldf8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-text-20-filled" /></template>
<style>
.obkkldf8r {
  fill: currentColor;
  d: path("M10 6.5V2H5.5A1.5 1.5 0 0 0 4 3.5v13A1.5 1.5 0 0 0 5.5 18h9a1.5 1.5 0 0 0 1.5-1.5V8h-4.5A1.5 1.5 0 0 1 10 6.5M6.5 10h7a.5.5 0 0 1 0 1h-7a.5.5 0 0 1 0-1m0 2h7a.5.5 0 0 1 0 1h-7a.5.5 0 0 1 0-1m0 2h7a.5.5 0 0 1 0 1h-7a.5.5 0 0 1 0-1M11 6.5V2.25L15.75 7H11.5a.5.5 0 0 1-.5-.5");
}

</style>
