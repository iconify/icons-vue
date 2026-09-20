<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="gx-qd5bsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:dock-left-28-regular" /></template>
<style>
.gx-qd5bsf {
  fill: currentColor;
  d: path("M5.754 4a3.75 3.75 0 0 0-3.75 3.75v11.5A3.75 3.75 0 0 0 5.754 23H22.25A3.75 3.75 0 0 0 26 19.25V7.75A3.75 3.75 0 0 0 22.25 4zm-2.25 3.75a2.25 2.25 0 0 1 2.25-2.25H9v16H5.754a2.25 2.25 0 0 1-2.25-2.25zM10.5 21.5v-16h11.75a2.25 2.25 0 0 1 2.25 2.25v11.5a2.25 2.25 0 0 1-2.25 2.25z");
}

</style>
