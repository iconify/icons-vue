<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="nk82fnb-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-step-in-diagonal-down-left-28-filled" /></template>
<style>
.nk82fnb-f {
  fill: currentColor;
  d: path("M23.78 5.28a.75.75 0 0 0-1.06-1.06l-9.22 9.22V7.75a.75.75 0 0 0-1.5 0v7.5c0 .414.336.75.75.75h7.5a.75.75 0 0 0 0-1.5h-5.69zM12 20a4 4 0 1 1-8 0a4 4 0 0 1 8 0");
}

</style>
