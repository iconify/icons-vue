<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fapkb76nf"/><path class="jh_4mgb1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kiwibank" /></template>
<style>
.fapkb76nf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.9 12.9h22.2v22.2H12.9z");
}

.jh_4mgb1s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.1 35.1h7.4V5.5H20.3L5.5 20.3v22.2h29.6z");
}

</style>
