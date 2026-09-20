<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="en40wleru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:app-unspan-28-filled" /></template>
<style>
.en40wleru {
  fill: currentColor;
  d: path("M8.75 2A2.75 2.75 0 0 0 6 4.75v5.129a2.25 2.25 0 0 1 2.841.28l3 3a2.25 2.25 0 0 1 0 3.182l-3 3a2.25 2.25 0 0 1-2.841.28v3.629A2.75 2.75 0 0 0 8.75 26h10.5A2.75 2.75 0 0 0 22 23.25v-3.63a2.25 2.25 0 0 1-2.841-.28l-3-3a2.25 2.25 0 0 1 0-3.182l3-3A2.25 2.25 0 0 1 22 9.879V4.75A2.75 2.75 0 0 0 19.25 2zM6.72 12.28L8.44 14H3.75a.75.75 0 0 0 0 1.5h4.69l-1.72 1.72a.75.75 0 1 0 1.06 1.06l3-3a.75.75 0 0 0 0-1.06l-3-3a.75.75 0 1 0-1.06 1.06m14.56 0L19.56 14h4.69a.75.75 0 0 1 0 1.5h-4.69l1.72 1.72a.75.75 0 1 1-1.06 1.06l-3-3a.75.75 0 0 1 0-1.06l3-3a.75.75 0 1 1 1.06 1.06");
}

</style>
