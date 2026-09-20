<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c69hz9g5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-maximize-32-regular" /></template>
<style>
.c69hz9g5c {
  fill: currentColor;
  d: path("M27 4a1 1 0 0 1 1 1v10a1 1 0 1 1-2 0V7.414L7.414 26H15a1 1 0 1 1 0 2H5a1 1 0 0 1-1-1V17a1 1 0 1 1 2 0v7.586L24.586 6H17a1 1 0 1 1 0-2z");
}

</style>
