<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r8hdihd_n"/><path class="g52_svobh"/><path class="nui9khh0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bixby-routines" /></template>
<style>
.g52_svobh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.892 31.266c-2.16 9.357-11.166 15.47-20.66 14.022c-9.493-1.447-16.269-9.965-15.543-19.54c.726-9.577 8.707-16.976 18.31-16.976");
}

.nui9khh0r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.18 2.5l6.748 6.315L24 15.56m0-6.788l6.928.043");
}

.r8hdihd_n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.914 22.641l10.634 9.84l16.343-16.768");
}

</style>
