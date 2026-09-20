<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rztvogblo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:filter-add-24-regular" /></template>
<style>
.rztvogblo {
  fill: currentColor;
  d: path("M13.5 16a.75.75 0 0 1 0 1.5h-3a.75.75 0 0 1 0-1.5zm4-14a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11m-5.478 9a6.5 6.5 0 0 0 1.325 1.5H7.5a.75.75 0 0 1 0-1.5zM17.5 3.999a.5.5 0 0 0-.5.5V7h-2.505a.5.5 0 0 0 0 1h2.506v2.504a.5.5 0 0 0 1 0V8h2.496a.5.5 0 0 0 0-1H18V4.499a.5.5 0 0 0-.5-.5M11.174 6A6.5 6.5 0 0 0 11 7.5H4.5a.75.75 0 0 1 0-1.5z");
}

</style>
