<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fb_zsdbra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-up-left-20-regular" /></template>
<style>
.fb_zsdbra {
  fill: currentColor;
  d: path("M11.5 4a.5.5 0 0 0 0-1h-8a.5.5 0 0 0-.5.5v8a.5.5 0 0 0 1 0V4.707l12.147 12.147a.5.5 0 0 0 .707-.708L4.707 4z");
}

</style>
