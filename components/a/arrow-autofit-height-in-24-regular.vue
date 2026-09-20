<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7lcypmwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-autofit-height-in-24-regular" /></template>
<style>
.g7lcypmwn {
  fill: currentColor;
  d: path("m16.78 9.78l2.5-2.5a.75.75 0 0 0-1.06-1.06L17 7.44V3.75a.75.75 0 0 0-1.5 0v3.69l-1.22-1.22a.75.75 0 1 0-1.06 1.06l2.5 2.5a.75.75 0 0 0 1.06 0M4 6.25A2.25 2.25 0 0 1 6.25 4h4a.75.75 0 0 1 0 1.5h-4a.75.75 0 0 0-.75.75v11.5c0 .414.336.75.75.75h4a.75.75 0 0 1 0 1.5h-4A2.25 2.25 0 0 1 4 17.75zm15.28 10.47l-2.5-2.5a.75.75 0 0 0-1.06 0l-2.5 2.5a.75.75 0 1 0 1.06 1.06l1.22-1.22v3.69a.75.75 0 0 0 1.5 0v-3.69l1.22 1.22a.75.75 0 1 0 1.06-1.06");
}

</style>
