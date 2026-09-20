<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="naowupbds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-right-circle-24-filled" /></template>
<style>
.naowupbds {
  fill: currentColor;
  d: path("M2 12C2 6.477 6.477 2 12 2s10 4.477 10 10s-4.477 10-10 10S2 17.523 2 12m7.97 4.53a.75.75 0 0 0 1.06 0l4-4a.75.75 0 0 0 0-1.06l-4-4a.75.75 0 1 0-1.06 1.06L13.44 12l-3.47 3.47a.75.75 0 0 0 0 1.06");
}

</style>
