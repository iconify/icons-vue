<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="auqqahv7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:border-top-bottom-24-regular" /></template>
<style>
.auqqahv7l {
  fill: currentColor;
  d: path("M3.75 7A.75.75 0 0 1 3 6.25v-.5A2.75 2.75 0 0 1 5.75 3h12.5A2.75 2.75 0 0 1 21 5.75v.5a.75.75 0 0 1-1.5 0v-.5c0-.69-.56-1.25-1.25-1.25H5.75c-.69 0-1.25.56-1.25 1.25v.5a.75.75 0 0 1-.75.75m.75 3.75a.75.75 0 0 0-1.5 0v2.5a.75.75 0 0 0 1.5 0zm15 0a.75.75 0 0 1 1.5 0v2.5a.75.75 0 0 1-1.5 0zm-16.5 7a.75.75 0 0 1 1.5 0v.5c0 .69.56 1.25 1.25 1.25h12.5c.69 0 1.25-.56 1.25-1.25v-.5a.75.75 0 0 1 1.5 0v.5A2.75 2.75 0 0 1 18.25 21H5.75A2.75 2.75 0 0 1 3 18.25z");
}

</style>
