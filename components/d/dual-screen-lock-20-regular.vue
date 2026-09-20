<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yhn_jcd9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:dual-screen-lock-20-regular" /></template>
<style>
.yhn_jcd9h {
  fill: currentColor;
  d: path("M14.5 3v1H14a1 1 0 0 0-1 1v4a1 1 0 0 0 1 1h5a1 1 0 0 0 1-1V5a1 1 0 0 0-1-1h-.5V3a2 2 0 1 0-4 0m1 1V3a1 1 0 1 1 2 0v1zm1 2.25a.75.75 0 1 1 0 1.5a.75.75 0 0 1 0-1.5M4 6h8v1h-1.5v10H16a1 1 0 0 0 1-1v-5h1v5a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2m2 9.5a.5.5 0 0 1 .5-.5h1a.5.5 0 0 1 0 1h-1a.5.5 0 0 1-.5-.5m6.5-.5a.5.5 0 0 0 0 1h1a.5.5 0 0 0 0-1zm-3-8H4a1 1 0 0 0-1 1v8a1 1 0 0 0 1 1h5.5z");
}

</style>
