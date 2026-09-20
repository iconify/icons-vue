<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e7sbwh53v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:add-32-filled" /></template>
<style>
.e7sbwh53v {
  fill: currentColor;
  d: path("M16 2.75c.69 0 1.25.56 1.25 1.25v10.75H28a1.25 1.25 0 1 1 0 2.5H17.25V28a1.25 1.25 0 1 1-2.5 0V17.25H4a1.25 1.25 0 1 1 0-2.5h10.75V4c0-.69.56-1.25 1.25-1.25");
}

</style>
