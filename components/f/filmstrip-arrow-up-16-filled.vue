<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bdt36ab_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:filmstrip-arrow-up-16-filled" /></template>
<style>
.bdt36ab_z {
  fill: currentColor;
  d: path("M11.5 7a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9m-.003 2a.5.5 0 0 0-.349.145l-2.002 2.002a.5.5 0 1 0 .708.707L11 10.707V13.5a.5.5 0 0 0 1 0v-2.793l1.146 1.146a.5.5 0 1 0 .707-.707l-2-2a.5.5 0 0 0-.35-.146zM12.5 2A2.5 2.5 0 0 1 15 4.5v2.757A5.5 5.5 0 0 0 6.023 12H3.5A2.5 2.5 0 0 1 1 9.5v-5A2.5 2.5 0 0 1 3.5 2zm-9 6a.5.5 0 0 0-.5.5v1a.5.5 0 0 0 1 0v-1a.5.5 0 0 0-.5-.5m0-4a.5.5 0 0 0-.5.5v1a.5.5 0 0 0 1 0v-1a.5.5 0 0 0-.5-.5m9 0a.5.5 0 0 0-.5.5v1a.5.5 0 0 0 1 0v-1a.5.5 0 0 0-.5-.5");
}

</style>
