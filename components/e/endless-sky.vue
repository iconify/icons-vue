<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uoqtcxeiw"/><path class="yam2s2bdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:endless-sky" /></template>
<style>
.uoqtcxeiw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 2.5l3.571 17.929L45.5 24l-17.929 3.571L24 45.5l-3.571-17.929L2.5 24l17.929-3.571z");
}

.yam2s2bdw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.488 13.512L29.062 24l5.426 10.488L24 29.062l-10.488 5.426L18.938 24l-5.426-10.488L24 18.938zm-13.046 9.055l.563-1.687m-.827 3.915l-.795-1.59m2.184 3.353l-1.687-.563m3.915.827l-1.59.795m3.353-2.184l-.563 1.687m.827-3.915l.795 1.59m-2.184-3.353l1.687.563m-3.915-.827l1.59-.795");
}

</style>
