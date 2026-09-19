<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mb_ft-b4o"/><path class="m56j6ybds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:avant-money" /></template>
<style>
.m56j6ybds {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.579 12.579H35.42V35.42H12.579z");
}

.mb_ft-b4o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 24v18.5H24C13.783 42.5 5.5 34.217 5.5 24S13.783 5.5 24 5.5S42.5 13.783 42.5 24");
}

</style>
