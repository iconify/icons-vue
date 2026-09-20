<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="bwvsu578c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:info-12-filled" /></template>
<style>
.bwvsu578c {
  fill: currentColor;
  d: path("M11 6A5 5 0 1 1 1 6a5 5 0 0 1 10 0m-5.5.5V8a.5.5 0 0 0 1 0V6.5a.5.5 0 0 0-1 0M6 3.75a.75.75 0 1 0 0 1.5a.75.75 0 0 0 0-1.5");
}

</style>
