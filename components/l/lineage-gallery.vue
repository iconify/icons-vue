<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="oxwggmi9r"/><path class="d_wzxnb8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lineage-gallery" /></template>
<style>
.d_wzxnb8c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.5 28.501l11.8-11.8l20.241 20.241M43.5 16.701l-13.6 13.6M35.529 11l-5.657 5.657l-5.601-5.601");
}

.oxwggmi9r {
  width: 39px;
  height: 26px;
  x: 4.5px;
  y: 11px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
}

</style>
