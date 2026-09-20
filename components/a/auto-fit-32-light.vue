<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i-fb-7spj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:auto-fit-32-light" /></template>
<style>
.i-fb-7spj {
  fill: currentColor;
  d: path("M6 4.5a.5.5 0 0 1 .5-.5h19a.5.5 0 0 1 0 1h-19a.5.5 0 0 1-.5-.5m0 23a.5.5 0 0 1 .5-.5h19a.5.5 0 0 1 0 1h-19a.5.5 0 0 1-.5-.5M16.854 7.146a.5.5 0 0 0-.708 0l-4 4a.5.5 0 0 0 .708.708L16 8.707v14.586l-3.646-3.647a.5.5 0 0 0-.708.708l4.5 4.5a.5.5 0 0 0 .708 0l4.5-4.5a.5.5 0 0 0-.708-.708L17 23.293V8.707l3.146 3.147a.5.5 0 0 0 .708-.708z");
}

</style>
