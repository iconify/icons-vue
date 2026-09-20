<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="e-u_kmu2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-infographic-16-regular" /></template>
<style>
.e-u_kmu2k {
  fill: currentColor;
  d: path("M11.5 2A2.5 2.5 0 0 1 14 4.5v7a2.5 2.5 0 0 1-2.5 2.5h-7A2.5 2.5 0 0 1 2 11.5v-7A2.5 2.5 0 0 1 4.5 2zm-7 1A1.5 1.5 0 0 0 3 4.5v7A1.5 1.5 0 0 0 4.5 13h7a1.5 1.5 0 0 0 1.5-1.5v-7A1.5 1.5 0 0 0 11.5 3zM6 7.5a2 2 0 1 1 0 4a2 2 0 0 1 0-4m3.5.5a.5.5 0 0 1 .5.5V11a.5.5 0 0 1-1 0V8.5a.5.5 0 0 1 .5-.5m2-1a.5.5 0 0 1 .5.5V11a.5.5 0 0 1-1 0V7.5a.5.5 0 0 1 .5-.5M6 8.5a1 1 0 1 0 0 2a1 1 0 0 0 0-2M11.5 5a.5.5 0 0 1 0 1h-7a.5.5 0 0 1 0-1z");
}

</style>
