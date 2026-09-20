<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="brtmhc3vv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-text-extract-28-regular" /></template>
<style>
.brtmhc3vv {
  fill: currentColor;
  d: path("M14.566 2a2.4 2.4 0 0 1 1.698.703l6.93 6.93A2.75 2.75 0 0 1 24 11.579V23.6a2.4 2.4 0 0 1-2.4 2.4H6.4A2.4 2.4 0 0 1 4 23.6V20h1.5v3.6a.9.9 0 0 0 .9.9h15.2a.9.9 0 0 0 .9-.9V12H16a2 2 0 0 1-2-2V3.5H6.4a.9.9 0 0 0-.9.9v12.1H4V4.4A2.4 2.4 0 0 1 6.4 2zm4.184 18.5a.75.75 0 0 1 0 1.5h-9.5a.75.75 0 0 1 0-1.5zm-6.5-3a.75.75 0 0 1 0 1.5h-9.5a.75.75 0 0 1 0-1.5zm6.5-3a.75.75 0 0 1 0 1.5h-9.5a.75.75 0 0 1 0-1.5zM15.5 10a.5.5 0 0 0 .5.5h5.94L15.5 4.06z");
}

</style>
