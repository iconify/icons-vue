<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j2-1-_b4k"/><path class="rf-m-rbys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:au-wifi-access" /></template>
<style>
.j2-1-_b4k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.5 31.302a8.193 8.193 0 0 1 13 0L24 36.29zM24 19.904a16.39 16.39 0 0 0-13 6.41c3.101-2.35 7.906-3.727 13-3.727s9.899 1.378 13 3.727a16.39 16.39 0 0 0-13-6.41");
}

.rf-m-rbys {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 15.289c-7.641 0-14.848 2.231-19.5 6.038a24.58 24.58 0 0 1 39 0c-4.652-3.807-11.859-6.038-19.5-6.038");
}

</style>
