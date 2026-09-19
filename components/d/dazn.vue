<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oud3lk9qo"/><path class="nj93ksb-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dazn" /></template>
<style>
.nj93ksb-x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.736 22.217V10.5h2.636a5.126 5.126 0 0 1 5.126 5.126v1.465a5.126 5.126 0 0 1-5.126 5.126ZM26.568 37.5V25.783L34.33 37.5V25.783m-20.66 0h7.762L13.67 37.5h7.762m5.209-15.318L30.529 10.5m3.728 11.717L30.529 10.5m2.481 7.797h-5.076");
}

.oud3lk9qo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 5.5h-37V20l4 4l-4 4v14.5h37V28l-4-4l4-4Z");
}

</style>
