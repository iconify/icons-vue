<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="loyh8sxeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:connected-28-filled" /></template>
<style>
.loyh8sxeb {
  fill: currentColor;
  d: path("M22.5 2a3.5 3.5 0 1 1-1.887 6.446l-3.666 3.667c.35.545.553 1.192.553 1.887s-.204 1.341-.554 1.886l3.667 3.667a3.5 3.5 0 1 1-1.06 1.06l-3.667-3.667A3.5 3.5 0 0 1 14 17.5a3.5 3.5 0 0 1-1.887-.553l-3.667 3.666a3.5 3.5 0 1 1-1.06-1.06l3.667-3.667A3.5 3.5 0 0 1 10.5 14c0-.695.203-1.342.553-1.887L7.386 8.446a3.5 3.5 0 1 1 1.06-1.06l3.667 3.667A3.5 3.5 0 0 1 14 10.5c.695 0 1.341.204 1.886.553l3.667-3.667A3.5 3.5 0 0 1 22.5 2");
}

</style>
