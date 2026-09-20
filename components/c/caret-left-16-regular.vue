<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="e3zuahu5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:caret-left-16-regular" /></template>
<style>
.e3zuahu5s {
  fill: currentColor;
  d: path("M9.429 11.864a1 1 0 0 0 1.57-.821V4.957a1 1 0 0 0-1.57-.821L5.644 6.769a1.5 1.5 0 0 0 0 2.462zm.57-.821L6.216 8.41a.5.5 0 0 1 0-.82L10 4.956z");
}

</style>
