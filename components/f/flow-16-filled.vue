<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mjy3fcbni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flow-16-filled" /></template>
<style>
.mjy3fcbni {
  fill: currentColor;
  d: path("M10.05 6H9.5a1 1 0 0 0-1 1v2a2 2 0 0 1-2 2h-.55a2.5 2.5 0 1 1 0-1h.55a1 1 0 0 0 1-1V7a2 2 0 0 1 2-2h.55a2.5 2.5 0 1 1 0 1");
}

</style>
