<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="krl7dabrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:battery-level" /></template>
<style>
.krl7dabrx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.8 4.5h4.1c.7 0 1.1.4 1.1 1.1v1.9h6.8c1.2 0 2.2 1 2.2 2.2v30.6c0 1.2-1 2.2-2.2 2.2H14.2c-1.2 0-2.2-1-2.2-2.2V9.7c0-1.2 1-2.2 2.2-2.2h6.4V5.6c.1-.7.6-1.1 1.2-1.1m-2.8 3h9.7");
}

</style>
