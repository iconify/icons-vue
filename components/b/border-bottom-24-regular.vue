<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9w-6ccqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:border-bottom-24-regular" /></template>
<style>
.p9w-6ccqg {
  fill: currentColor;
  d: path("M6.25 3a.75.75 0 0 1 0 1.5h-.5c-.69 0-1.25.56-1.25 1.25v.5a.75.75 0 0 1-1.5 0v-.5A2.75 2.75 0 0 1 5.75 3zm11.5 0a.75.75 0 0 0 0 1.5h.5c.69 0 1.25.56 1.25 1.25v.5a.75.75 0 0 0 1.5 0v-.5A2.75 2.75 0 0 0 18.25 3zm-14 7a.75.75 0 0 1 .75.75v2.5a.75.75 0 0 1-1.5 0v-2.5a.75.75 0 0 1 .75-.75m15.75.75a.75.75 0 0 1 1.5 0v2.5a.75.75 0 0 1-1.5 0zm-5.5-7a.75.75 0 0 1-.75.75h-2.5a.75.75 0 0 1 0-1.5h2.5a.75.75 0 0 1 .75.75m-11 14a.75.75 0 0 1 1.5 0v.5c0 .69.56 1.25 1.25 1.25h12.5c.69 0 1.25-.56 1.25-1.25v-.5a.75.75 0 0 1 1.5 0v.5A2.75 2.75 0 0 1 18.25 21H5.75A2.75 2.75 0 0 1 3 18.25z");
}

</style>
