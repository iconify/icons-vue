<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ptg532byr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:equal-circle-16-filled" /></template>
<style>
.ptg532byr {
  fill: currentColor;
  d: path("M15 8A7 7 0 1 1 1 8a7 7 0 0 1 14 0M4.5 6.5A.5.5 0 0 0 5 7h6a.5.5 0 0 0 0-1H5a.5.5 0 0 0-.5.5M5 9a.5.5 0 0 0 0 1h6a.5.5 0 0 0 0-1z");
}

</style>
