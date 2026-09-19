<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wiwys33-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:atalaya" /></template>
<style>
.wiwys33-p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 38.976v-1.155s-3.806-6.087-15.488-7.492l-1.29-15.575s1.172-.117 1.172-.43c0-.214.046-1.102-.581-1.102l-.161-2.054L24 9.025l-2.15 2.143l-.162 2.054c-.627 0-.581.887-.581 1.103c0 .312 1.173.429 1.173.429l-1.291 15.575C9.306 31.734 5.5 37.82 5.5 37.82v1.155Z");
}

</style>
