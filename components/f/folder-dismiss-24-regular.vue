<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pfjjl5gzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:folder-dismiss-24-regular" /></template>
<style>
.pfjjl5gzn {
  fill: currentColor;
  d: path("M17.5 12a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11M8.129 3a2.25 2.25 0 0 1 1.59.66l1.842 1.84h7.189A3.25 3.25 0 0 1 22 8.75v4.062a6.5 6.5 0 0 0-1.5-1.079V8.75A1.75 1.75 0 0 0 18.75 7h-7.19L9.72 8.84a2.25 2.25 0 0 1-1.591.66H3.5v8.25c0 .966.784 1.75 1.75 1.75h6.065a6.4 6.4 0 0 0 .71 1.5H5.25A3.25 3.25 0 0 1 2 17.75V6.25A3.25 3.25 0 0 1 5.25 3zm11.725 12.147a.5.5 0 0 0-.707 0L17.5 16.793l-1.646-1.646a.5.5 0 1 0-.707.707l1.646 1.646l-1.646 1.646a.5.5 0 1 0 .707.707l1.646-1.646l1.646 1.646a.5.5 0 1 0 .707-.707L18.208 17.5l1.646-1.646a.5.5 0 0 0 0-.707M5.25 4.5A1.75 1.75 0 0 0 3.5 6.25V8h4.629a.75.75 0 0 0 .53-.22l1.53-1.53l-1.53-1.53a.75.75 0 0 0-.53-.22z");
}

</style>
