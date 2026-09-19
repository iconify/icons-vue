<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d4w5ybcxu"/><path class="v2qtvkb4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:docx-reader" /></template>
<style>
.d4w5ybcxu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.81 20.072l-2.13 8.519l-2.13-8.519l-2.129 8.519l-2.13-8.519M28.015 9.985h14.41v27.623h-14.41zm0 4.034h10.25m-10.25 3.734h10.25m-10.25 4.003h10.25m-10.25 3.734h10.25m-10.25 3.659h10.25m-10.25 3.987h10.25");
}

.v2qtvkb4k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.015 41.329V6.699c-.089-.855-.175-1.172-1.2-1.199L6.713 8.592c-.256.117-.994.131-1.136 1.085V37.67c.066.901-.168 1.132.757 1.262L26.4 42.466c.463 0 1.519.347 1.616-1.136");
}

</style>
