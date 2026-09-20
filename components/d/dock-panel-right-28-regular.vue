<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="m8g7_wh4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:dock-panel-right-28-regular" /></template>
<style>
.m8g7_wh4u {
  fill: currentColor;
  d: path("M22.246 4a3.75 3.75 0 0 1 3.75 3.75v11.5a3.75 3.75 0 0 1-3.75 3.75H5.75A3.75 3.75 0 0 1 2 19.25V7.75A3.75 3.75 0 0 1 5.75 4zm2.25 3.75a2.25 2.25 0 0 0-2.25-2.25H19v16h3.246a2.25 2.25 0 0 0 2.25-2.25zM17.5 21.5v-16H5.75A2.25 2.25 0 0 0 3.5 7.75v11.5a2.25 2.25 0 0 0 2.25 2.25z");
}

</style>
