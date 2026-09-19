<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="le1ad3bkb"/><path class="qdd1a8bgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kustom-konsole" /></template>
<style>
.le1ad3bkb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 33.698h-39V14.302h39l-9.559 10.01z");
}

.qdd1a8bgg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.052 14.302l-9.559 10.01l9.559 9.386");
}

</style>
