<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l5cj4hbny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:copy-select-24-filled" /></template>
<style>
.l5cj4hbny {
  fill: currentColor;
  d: path("M8.5 13.75A4.25 4.25 0 0 0 12.75 18h1.75v.75A3.25 3.25 0 0 1 11.25 22h-6A3.25 3.25 0 0 1 2 18.75v-8.5A3.25 3.25 0 0 1 5.25 7H8.5zm1.75-.75a.75.75 0 0 1 .75.75v.5c0 .69.56 1.25 1.25 1.25a.75.75 0 0 1 0 1.5a2.75 2.75 0 0 1-2.75-2.75v-.5a.75.75 0 0 1 .75-.75m6 2.5a.75.75 0 0 1 0 1.5h-1a.75.75 0 0 1 0-1.5zm5-2.5a.75.75 0 0 1 .75.75v.5A2.75 2.75 0 0 1 19.25 17a.75.75 0 0 1 0-1.5c.69 0 1.25-.56 1.25-1.25v-.5a.75.75 0 0 1 .75-.75m-11-5.5a.75.75 0 0 1 .75.75v2.5a.75.75 0 0 1-1.5 0v-2.5a.75.75 0 0 1 .75-.75m11 0a.75.75 0 0 1 .75.75v2.5a.75.75 0 0 1-1.5 0v-2.5a.75.75 0 0 1 .75-.75m-9-5.5a.75.75 0 0 1 0 1.5c-.69 0-1.25.56-1.25 1.25v.5a.75.75 0 0 1-1.5 0v-.5A2.75 2.75 0 0 1 12.25 2m7 0A2.75 2.75 0 0 1 22 4.75v.5a.75.75 0 0 1-1.5 0v-.5c0-.69-.56-1.25-1.25-1.25a.75.75 0 0 1 0-1.5m-3 0a.75.75 0 0 1 0 1.5h-1a.75.75 0 0 1 0-1.5z");
}

</style>
