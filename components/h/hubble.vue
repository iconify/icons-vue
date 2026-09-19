<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="r_tgscb2s"/><path class="rbb7-zctd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hubble" /></template>
<style>
.r_tgscb2s {
  cx: 35.51px;
  cy: 34.906px;
  r: 6.99px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.rbb7-zctd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.966 41.879a7.99 7.99 0 0 1-7.136-5.75c-.934-3.226.227-6.554 2.076-8.64s18-19.578 18-19.578c1.572-1.951 3.56-2.238 5.295-1.29c1.335.73 2.158 2.582 1.145 4.874L21.298 36.397c-2.13 4.347-4.982 5.708-8.332 5.482");
}

</style>
