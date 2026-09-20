<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bytbbkbcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:hard-drive-24-filled" /></template>
<style>
.bytbbkbcs {
  fill: currentColor;
  d: path("M7.44 4a2.25 2.25 0 0 0-2.025 1.27L2.73 10.821c.465-.206.98-.321 1.521-.321h15.5a3.7 3.7 0 0 1 1.52.321L18.586 5.27A2.25 2.25 0 0 0 16.559 4zm12.31 8A2.25 2.25 0 0 1 22 14.25v2.5A2.25 2.25 0 0 1 19.75 19H4.25A2.25 2.25 0 0 1 2 16.75v-2.5A2.25 2.25 0 0 1 4.25 12zm-1.25 4.5a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

</style>
