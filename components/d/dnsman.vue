<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jnhj88biz"/><path class="ocm5shbja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dnsman" /></template>
<style>
.jnhj88biz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.64 18.75h14.72m-14.72-3.76h14.72m-14.72-3.76h14.72M16.64 7.47h14.72M33.75 25a2 2 0 0 0-2-2h-15.5a2 2 0 0 0-2 2");
}

.ocm5shbja {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42 25h-8.25V7.33a2.83 2.83 0 0 0-2.83-2.83H17.08a2.83 2.83 0 0 0-2.83 2.83V25H6a1.47 1.47 0 0 0 0 2.9h8.29v12.77a2.83 2.83 0 0 0 2.83 2.83h13.8a2.83 2.83 0 0 0 2.83-2.83V27.9H42a1.47 1.47 0 0 0 0-2.9");
}

</style>
