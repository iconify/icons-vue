<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xwqq1nb0k"/><path class="ti2x76bqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:eufyhome" /></template>
<style>
.ti2x76bqv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 26.11l6.437-6.436a9.103 9.103 0 1 0 2.666 6.436");
}

.xwqq1nb0k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.192 14.546L25.171 5.96a2.48 2.48 0 0 0-2.341 0L6.808 14.546A2.48 2.48 0 0 0 5.5 16.73v23.125a2.48 2.48 0 0 0 2.478 2.478h32.044a2.48 2.48 0 0 0 2.478-2.478V16.73a2.48 2.48 0 0 0-1.308-2.184");
}

</style>
