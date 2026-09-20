<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i92fxpbnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-agenda-16-filled" /></template>
<style>
.i92fxpbnx {
  fill: currentColor;
  d: path("M11.5 2A2.5 2.5 0 0 1 14 4.5v7a2.5 2.5 0 0 1-2.5 2.5h-7A2.5 2.5 0 0 1 2 11.5v-7A2.5 2.5 0 0 1 4.5 2zm-6 8a.5.5 0 0 0 0 1h5a.5.5 0 0 0 0-1zm0-2.5a.5.5 0 0 0 0 1h5a.5.5 0 0 0 0-1zm0-2.5a.5.5 0 0 0 0 1h5a.5.5 0 0 0 0-1z");
}

</style>
