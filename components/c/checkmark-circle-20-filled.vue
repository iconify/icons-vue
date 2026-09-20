<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wuc88ebgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:checkmark-circle-20-filled" /></template>
<style>
.wuc88ebgk {
  fill: currentColor;
  d: path("M10 2a8 8 0 1 1 0 16a8 8 0 0 1 0-16m3.358 5.646a.5.5 0 0 0-.637-.057l-.07.057L9 11.298L7.354 9.651l-.07-.058a.5.5 0 0 0-.695.696l.057.07l2 2l.07.057a.5.5 0 0 0 .568 0l.07-.058l4.004-4.004l.058-.07a.5.5 0 0 0-.058-.638");
}

</style>
