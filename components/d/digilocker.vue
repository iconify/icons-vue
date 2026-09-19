<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tgsd0jv9k"/><path class="o9s-xjpcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:digilocker" /></template>
<style>
.o9s-xjpcw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.397 21.925c-.043 0-.084.005-.126.006a7.218 7.218 0 0 0-13.488-2.166c-.043-.001-.085-.007-.129-.007a6.154 6.154 0 0 0 0 12.308h13.743a5.07 5.07 0 1 0 0-10.14");
}

.tgsd0jv9k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.5 31.19V41.5a2 2 0 0 0 2 2h27a2 2 0 0 0 2-2v-26h-9a2 2 0 0 1-2-2v-9h-18a2 2 0 0 0-2 2v14.135M28.5 4.5l11 11");
}

</style>
