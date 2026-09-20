<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="w6jnrvbmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:battery-0-28-regular" /></template>
<style>
.w6jnrvbmc {
  fill: currentColor;
  d: path("M5.75 7A3.75 3.75 0 0 0 2 10.75v6.5A3.75 3.75 0 0 0 5.75 21h14.5A3.75 3.75 0 0 0 24 17.25V16h1a1 1 0 0 0 1-1v-2a1 1 0 0 0-1-1h-1v-1.25A3.75 3.75 0 0 0 20.25 7zM3.5 10.75A2.25 2.25 0 0 1 5.75 8.5h14.5a2.25 2.25 0 0 1 2.25 2.25v6.5a2.25 2.25 0 0 1-2.25 2.25H5.75a2.25 2.25 0 0 1-2.25-2.25z");
}

</style>
