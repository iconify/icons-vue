<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o3u7ecbrj"/><path class="lqq1c_bvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:luci-mobile" /></template>
<style>
.lqq1c_bvk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.5 31.502h3v3h-3zm5.5 0h3v3h-3zm5.5 0h3v3h-3z");
}

.o3u7ecbrj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.5 26.502v-4.5c0-2.5 3-2.5 3 0v4.5h5c1.662 0 3 1.338 3 3v6c0 1.661-1.338 3-3 3h-27c-1.662 0-3-1.339-3-3v-6c0-1.662 1.338-3 3-3zm-4.157-10.16a8 8 0 0 1 11.314 0m-14.142-3.328c4.686-4.687 12.284-4.687 16.97 0h.001");
}

</style>
