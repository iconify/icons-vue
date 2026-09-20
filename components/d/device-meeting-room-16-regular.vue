<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tmz-0g8qt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:device-meeting-room-16-regular" /></template>
<style>
.tmz-0g8qt {
  fill: currentColor;
  d: path("M4.665 2c-.896 0-1.683.596-1.926 1.459l-1.66 5.898A2.08 2.08 0 0 0 3.083 12h9.834a2.08 2.08 0 0 0 2.004-2.643l-1.66-5.898A2 2 0 0 0 11.335 2zm-.963 1.73A1 1 0 0 1 4.665 3h6.67a1 1 0 0 1 .963.73l1.66 5.898A1.08 1.08 0 0 1 12.918 11H3.082a1.08 1.08 0 0 1-1.04-1.372zM4.497 13a.5.5 0 1 0 0 1h7.005a.5.5 0 1 0 0-1z");
}

</style>
