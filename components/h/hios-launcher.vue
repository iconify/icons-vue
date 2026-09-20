<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nqyqhkbhq"/><circle class="wj7xi2bcw"/><path class="xp4uz-r6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hios-launcher" /></template>
<style>
.nqyqhkbhq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h29c2.2 0 4-1.8 4-4v-29c0-2.2-1.8-4-4-4m-29 13.6v10.4m6.9-10.4v10.4m-6.9-5.2h4.1");
}

.wj7xi2bcw {
  cx: 19.3px;
  cy: 19.4px;
  r: 0.8px;
  fill: currentColor;
}

.xp4uz-r6e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.3 22.6v6.9m12.5-1.2c.6.8 1.4 1.1 2.5 1.1h1.5c1.4 0 2.6-1.2 2.6-2.6s-1.2-2.6-2.6-2.6h-1.7c-1.4 0-2.6-1.2-2.6-2.6s1.2-2.6 2.6-2.6h1.5c1.1 0 1.9.3 2.5 1.1m-12.4-1zc1.9 0 3.4 1.5 3.4 3.4V26c0 1.9-1.5 3.4-3.4 3.4s-3.4-1.5-3.4-3.4v-3.5c0-1.9 1.5-3.4 3.4-3.4");
}

</style>
