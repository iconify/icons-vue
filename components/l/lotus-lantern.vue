<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w9omg4bjw"/><path class="xs21xmocc"/><path class="ugeueobgw"/><path class="t3f7ucblk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lotus-lantern" /></template>
<style>
.t3f7ucblk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.007 29.826c3.371-4.634 7.54-7.724 13.438-7.628c.564 4.478-3.316 9.54-8.748 13.547m-6.761 3.502l-7.069-7.085l-3.17 3.178H30.71l-3.17-3.178l-7.07 7.085");
}

.ugeueobgw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.993 29.826c-3.371-4.634-7.54-7.724-13.438-7.628c-.564 4.478 3.316 9.54 8.748 13.547m21.504-6.121c2.918-6.004 3.06-11.465 1.036-15.74c-4.886 1.787-6.922 7.065-8.327 12.88");
}

.w9omg4bjw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.052 28.776c-2.344-7.842.63-16.238 4.866-20.023c5.442 4.466 5.364 12.628 4.685 20.152");
}

.xs21xmocc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.193 29.624c-2.918-6.004-3.06-11.465-1.036-15.74c4.886 1.787 6.922 7.065 8.327 12.88");
}

</style>
