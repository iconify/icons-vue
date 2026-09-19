<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="blz5s3b7n"/><path class="lkpsrr46i"/><path class="cfju6ubpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bump" /></template>
<style>
.blz5s3b7n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 27.503l8.117 3.252c3.387 1.357 6.525-2.425 4.566-5.504l-7.982-12.544c-2.19-3.44-7.212-3.44-9.402 0L11.317 25.25c-1.96 3.079 1.178 6.86 4.566 5.504z");
}

.cfju6ubpg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 30.879v6.2h0c.03 3.66 3.764 6.756 7.72 5.24L24 38.187l10.78 4.132c3.956 1.516 7.69-1.58 7.72-5.24h0v-6.2");
}

.lkpsrr46i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 32.063l10.78 4.132c4.966 1.903 9.583-3.462 6.96-8.088L31.17 9.463c-3.158-5.569-11.182-5.569-14.34 0L6.26 28.107c-2.623 4.626 1.994 9.991 6.96 8.088z");
}

</style>
