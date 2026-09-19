<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tfzf01yfy"/><path class="tdnbom_tq"/><path class="j3d6tcseq"/><path class="dhsf88b9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:air-travel" /></template>
<style>
.dhsf88b9i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.632 17.867c-24 14.258 44.652 10.286 32.387-4.832");
}

.j3d6tcseq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.632 17.867c-4.465 8.355 34.035 4.751 32.387-4.832");
}

.tdnbom_tq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.882 6.987h10.202v23.321c0 4.788 1.258 7.849 4.447 10.705c-8.972 0-14.65-1.218-14.65-8.478Z");
}

.tfzf01yfy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.353 33.246c2.734 0 4.903-.421 4.903-4.125V6.988h10.117v26.735c0 4.026-3.104 7.291-10.842 7.291");
}

</style>
