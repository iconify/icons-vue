<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k2939dwgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:code-off-16-filled" /></template>
<style>
.k2939dwgx {
  fill: currentColor;
  d: path("M1.146 1.147a.5.5 0 0 1 .707 0l13 13a.5.5 0 0 1-.707.707L8.073 8.779l-1.787 4.025a.75.75 0 0 1-1.371-.61l2.022-4.551L4.61 5.317a.75.75 0 0 1-.05.931L3.004 8L4.56 9.751a.75.75 0 0 1-1.122.997l-2-2.25a.75.75 0 0 1 0-.997l2-2.25a.75.75 0 0 1 .985-.12L1.146 1.854a.5.5 0 0 1 0-.707m10.356 4.042a.75.75 0 0 1 1.058.062l2 2.25a.75.75 0 0 1 0 .997l-1.854 2.086l-1.063-1.063l1.353-1.522l-1.557-1.75a.75.75 0 0 1 .063-1.06M8.914 3.194a.75.75 0 0 1 1.371.61L8.943 6.82L7.807 5.685z");
}

</style>
