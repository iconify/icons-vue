<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r7zhvgbgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kakao-story" /></template>
<style>
.r7zhvgbgr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.677 43.5h22.646M17.707 33.44l8.808 3.767q7.545-8.809 7.545-18.869V4.5H13.94v15.102h8.797Q24 27.147 17.707 33.44");
}

</style>
