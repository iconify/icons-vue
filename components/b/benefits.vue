<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="imesovblg"/><path class="ntta8cbbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:benefits" /></template>
<style>
.imesovblg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.416 18.662c0 7.268 5.892 13.16 13.16 13.16h7.965V5.5h-7.964c-7.269 0-13.161 5.893-13.161 13.161");
}

.ntta8cbbk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.585 21.736a6.92 6.92 0 0 0-6.922-6.922H19.336V42.5h13.327a6.922 6.922 0 0 0 0-13.843a6.92 6.92 0 0 0 6.922-6.921");
}

</style>
