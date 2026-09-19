<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f4sfjxddc"/><path class="m49pvabxw"/><path class="hyw5of31j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:aftership" /></template>
<style>
.f4sfjxddc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 13.264l7.288 4.21L24 21.681l-7.288-4.209Z");
}

.hyw5of31j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.905 21.405a16.905 16.905 0 1 0-23.389 15.611L24 43.5l6.484-6.484a16.91 16.91 0 0 0 10.42-15.611");
}

.m49pvabxw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.712 17.473v8.418L24 30.101l7.288-4.21v-8.418M24 30.1v-8.418");
}

</style>
