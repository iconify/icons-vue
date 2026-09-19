<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="os_efjbia"/><circle class="v96yovgek"/><path class="kxzja4rlt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:colizeum" /></template>
<style>
.kxzja4rlt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m11.305 27.182l6.364-6.364m0 6.364l-6.364-6.364");
}

.os_efjbia {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.987 2.5A21.5 21.5 0 0 0 3.69 17h40.62A21.5 21.5 0 0 0 23.988 2.5M3.69 31a21.5 21.5 0 0 0 20.297 14.5A21.5 21.5 0 0 0 44.284 31H26.487l-2.5-4l-2.5 4z");
}

.v96yovgek {
  cx: 33.486px;
  cy: 24px;
  r: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
