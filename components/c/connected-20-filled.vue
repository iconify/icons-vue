<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wqmpazehl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:connected-20-filled" /></template>
<style>
.wqmpazehl {
  fill: currentColor;
  d: path("M7 4.5c0 .51-.152.983-.414 1.379L8.62 7.914A2.5 2.5 0 0 1 9.999 7.5c.51 0 .983.152 1.379.414l2.035-2.035a2.5 2.5 0 1 1 .707.707L12.086 8.62c.262.396.414.87.414 1.379c0 .51-.152.983-.414 1.379l2.035 2.035a2.5 2.5 0 1 1-.707.707l-2.035-2.035a2.5 2.5 0 0 1-1.379.414c-.51 0-.983-.152-1.379-.414L6.586 14.12a2.5 2.5 0 1 1-.707-.707l2.035-2.035A2.5 2.5 0 0 1 7.5 10c0-.51.152-.983.414-1.379L5.88 6.586A2.5 2.5 0 1 1 7 4.5");
}

</style>
