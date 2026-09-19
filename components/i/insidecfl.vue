<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bs82izbfp"/><path class="cgeesc7og"/><path class="efteg3r9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:insidecfl" /></template>
<style>
.bs82izbfp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.157 17.072H15.368c-1.384 0-2.186.376-2.805 1.334l-3.142 4.869c-.77 1.193-.539 2.21 1.077 2.21h7.136");
}

.cgeesc7og {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.04 20.334l-6.904.01l-3.297 5.208m15.278-8.466l-5.46 8.394h9.346");
}

.efteg3r9v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 29.98V12.4c0-2.477 1.57-3.795 3.795-3.795h31.437c2.544 0 3.768 1.574 3.768 3.768v18.04c0 2.073-1.27 3.663-3.663 3.663H32.94L22.415 41.11c-1.139.762-1.992-.14-1.351-1.127l3.831-5.907H8.377C5.9 34.076 4.5 32.65 4.5 29.98");
}

</style>
