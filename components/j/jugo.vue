<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="lli1p34ay"/><path class="syrapbbby"/><path class="qrx_qacah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:jugo" /></template>
<style>
.lli1p34ay {
  cx: 24px;
  cy: 11.207px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 18.5px;
  ry: 2.706px;
}

.qrx_qacah {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.547 24.128c-2.98 7.308-7.573 12.25-15.547 12.25s-12.567-4.942-15.547-12.25m32.966-8.187c-9.241-2.028-11.666.877-17.419.877s-8.177-2.905-17.419-.877m.542 2.374c17.18 6.6 24.382-2.69 33.854-.462");
}

.syrapbbby {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m42.5 11.207l-5.862 25.586C36.304 38.25 30.98 39.499 24 39.499s-12.3-1.25-12.638-2.706A12967 12967 0 0 1 5.5 11.207");
}

</style>
