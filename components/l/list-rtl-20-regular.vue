<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a0x1xufqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:list-rtl-20-regular" /></template>
<style>
.a0x1xufqa {
  fill: currentColor;
  d: path("M6 4.5a.5.5 0 0 1 .5-.5h11a.5.5 0 0 1 0 1h-11a.5.5 0 0 1-.5-.5m1 10a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1h-10a.5.5 0 0 1-.5-.5M2.5 9a.5.5 0 0 0 0 1h15a.5.5 0 0 0 0-1z");
}

</style>
