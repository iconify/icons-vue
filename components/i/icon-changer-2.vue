<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wj5jh2bfj"/><path class="crtpp2b8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:icon-changer-2" /></template>
<style>
.crtpp2b8c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.5 14a2.5 2.5 0 0 1 2.5 2.5v15a2.5 2.5 0 0 1-2.5 2.5c-5.493 0-10-4.507-10-10s4.507-10 10-10");
}

.wj5jh2bfj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 5.5C13.783 5.5 5.5 13.783 5.5 24S13.783 42.5 24 42.5h14.379c2.216 0 4-1.784 4-4L42.5 24c0-10.217-8.283-18.5-18.5-18.5");
}

</style>
