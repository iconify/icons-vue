<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="po936wbwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:key-visualizer-sharp" /></template>
<style>
.po936wbwp {
  fill: currentColor;
  d: path("M3 21v-2h3v2zm0-4v-2h8v2zm0-4v-2h18v2zm0-4V7h8v2zm0-4V3h3v2zm5 16v-2h3v2zM8 5V3h3v2zm5 16v-2h3v2zm0-4v-2h8v2zm0-8V7h8v2zm0-4V3h3v2zm5 16v-2h3v2zm0-16V3h3v2z");
}

</style>
