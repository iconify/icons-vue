<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xgholzbkq"/><path class="aan_iosrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kasa" /></template>
<style>
.aan_iosrv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.964 42.022V25.434a4.6 4.6 0 0 0-1.351-3.263L18.233 10.79m1.196 31.232V25.434a4.6 4.6 0 0 0-1.352-3.263l-5.613-5.613");
}

.xgholzbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.369 6.654L6.852 22.17A4.6 4.6 0 0 0 5.5 25.433v14.282a2.307 2.307 0 0 0 2.307 2.307h32.386a2.307 2.307 0 0 0 2.307-2.307V25.433a4.6 4.6 0 0 0-1.351-3.262L25.63 6.654a2.307 2.307 0 0 0-3.262 0");
}

</style>
