<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="onnqm4mxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:device-meeting-room-all-in-one-24-filled" /></template>
<style>
.onnqm4mxo {
  fill: currentColor;
  d: path("M21 17.75A3.25 3.25 0 0 1 17.75 21H6.25A3.25 3.25 0 0 1 3 17.75V16h18zM17.75 3A3.25 3.25 0 0 1 21 6.25v8.25H3V6.25A3.25 3.25 0 0 1 6.25 3zM12 6.75a1.25 1.25 0 1 0 0 2.5a1.25 1.25 0 0 0 0-2.5");
}

</style>
