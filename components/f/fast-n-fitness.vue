<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="esypvvuxm"/><path class="s_wg3vbmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fast-n-fitness" /></template>
<style>
.esypvvuxm {
  cx: 24px;
  cy: 17.973px;
  r: 2.904px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.s_wg3vbmf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.317 41.778L24 31.108l4.683 10.67M24 31.108v-6.75m8.581-8.893L24 24.36l-8.581-8.894m-2.574-1.91h22.368M36.71 8.7v9.713M11.423 8.7v9.713M38.198 8.7v9.713m1.487-7.538v5.362M9.936 8.7v9.713M8.45 10.875v5.362");
}

</style>
