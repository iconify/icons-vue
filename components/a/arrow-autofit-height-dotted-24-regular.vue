<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iflnsgb7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-autofit-height-dotted-24-regular" /></template>
<style>
.iflnsgb7c {
  fill: currentColor;
  d: path("M18.72 17.22a.75.75 0 0 1 1.06 1.06l-2.5 2.5a.75.75 0 0 1-1.06 0l-2.5-2.5a.75.75 0 0 1 1.06-1.06l1.97 1.97zM11.25 4a.75.75 0 0 1 0 1.5h-5a.75.75 0 0 0-.75.75v11.5c0 .414.336.75.75.75h5a.75.75 0 0 1 0 1.5h-5A2.25 2.25 0 0 1 4 17.75V6.25A2.25 2.25 0 0 1 6.25 4zm5.5 10.5a.75.75 0 0 1 .75.75v1a.75.75 0 0 1-1.5 0v-1a.75.75 0 0 1 .75-.75m0-3.5a.75.75 0 0 1 .75.75v.5a.75.75 0 0 1-1.5 0v-.5a.75.75 0 0 1 .75-.75m0-4a.75.75 0 0 1 .75.75v1a.75.75 0 0 1-1.5 0v-1a.75.75 0 0 1 .75-.75m-.474-3.832a.75.75 0 0 1 1.004.052l2.5 2.5a.75.75 0 0 1-1.06 1.06l-1.97-1.97l-1.97 1.97a.75.75 0 0 1-1.06-1.06l2.5-2.5z");
}

</style>
