<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9robjj2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:clover-24-filled" /></template>
<style>
.w9robjj2e {
  fill: currentColor;
  d: path("M6.75 2a4.75 4.75 0 0 0 0 9.5h4a.75.75 0 0 0 .75-.75v-4A4.75 4.75 0 0 0 6.75 2m0 20a4.75 4.75 0 1 1 0-9.5h4a.75.75 0 0 1 .75.75v4A4.75 4.75 0 0 1 6.75 22m10.5-20a4.75 4.75 0 1 1 0 9.5h-4a.75.75 0 0 1-.75-.75v-4A4.75 4.75 0 0 1 17.25 2m0 20a4.75 4.75 0 1 0 0-9.5h-4a.75.75 0 0 0-.75.75v4A4.75 4.75 0 0 0 17.25 22");
}

</style>
