<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jaxzql63r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-left-32-regular" /></template>
<style>
.jaxzql63r {
  fill: currentColor;
  d: path("M20.707 5.293a1 1 0 0 1 0 1.414L11.414 16l9.293 9.293a1 1 0 0 1-1.414 1.414l-10-10a1 1 0 0 1 0-1.414l10-10a1 1 0 0 1 1.414 0");
}

</style>
