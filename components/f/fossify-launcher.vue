<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="fjygokbka"/><path class="d7j7tjo0s"/></g><path class="qjgg8actc"/><path class="p8fe-8bxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fossify-launcher" /></template>
<style>
.d7j7tjo0s {
  d: path("M37.47 18.875v16.121a3.66 3.66 0 0 1-3.67 3.668h-2.228a3.66 3.66 0 0 1-3.67-3.668v-3.891");
}

.fjygokbka {
  d: path("m20.637 31.158l-.403 3.838c-.212 2.021-1.637 3.668-3.67 3.668h-2.229a3.66 3.66 0 0 1-3.67-3.668V18.77m17.237 12.335c0-1.714-.45-3.641-3.633-3.641s-3.452 1.977-3.632 3.694");
}

.p8fe-8bxs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 22.767L22.114 9.913c.994-.77 2.778-.77 3.772 0L42.5 22.767m-8.013-12.345v6.144");
}

.qjgg8actc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.144 19.59c.21-1.808 1.873-3.18 3.856-3.18s3.647 1.372 3.856 3.18z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
