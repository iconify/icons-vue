<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mnntot7qu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-step-in-diagonal-down-left-24-filled" /></template>
<style>
.mnntot7qu {
  fill: currentColor;
  d: path("M19.78 4.28a.75.75 0 0 0-1.06-1.06l-8.22 8.22V5.75a.75.75 0 0 0-1.5 0v7.5c0 .414.336.75.75.75h7.5a.75.75 0 0 0 0-1.5h-5.69zM9 18a3 3 0 1 1-6 0a3 3 0 0 1 6 0");
}

</style>
