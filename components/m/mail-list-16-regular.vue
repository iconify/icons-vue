<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l4z4g6bvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mail-list-16-regular" /></template>
<style>
.l4z4g6bvi {
  fill: currentColor;
  d: path("M9 2.5a.5.5 0 0 1 .5-.5h5a.5.5 0 0 1 0 1h-5a.5.5 0 0 1-.5-.5m0 2a.5.5 0 0 1 .5-.5h5a.5.5 0 0 1 0 1h-5a.5.5 0 0 1-.5-.5m0 2a.5.5 0 0 1 .5-.5h5a.5.5 0 0 1 0 1h-5a.5.5 0 0 1-.5-.5M4 3h4.085c.066.186.168.356.297.5c-.13.144-.23.314-.297.5H4a1 1 0 0 0-1 1v.74l5 2.692l.977-.526c.163.06.339.094.523.094h1.412L8.237 9.44a.5.5 0 0 1-.474 0L3 6.876V11a1 1 0 0 0 1 1h8a1 1 0 0 0 1-1V8h1v3a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2");
}

</style>
