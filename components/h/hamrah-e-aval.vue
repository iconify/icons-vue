<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sukj6gb5m"/><path class="q9r31vbyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hamrah-e-aval" /></template>
<style>
.q9r31vbyh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.27 28.8c-5.06 2.234-8.178 4.665-7.727 6.389c.697 2.664 9.652 2.63 20.001-.077s18.176-7.06 17.479-9.725c-.382-1.461-3.251-2.11-7.473-1.952");
}

.sukj6gb5m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.127 23.768c6.52-5.084 10.442-10.125 9.116-12.107c-1.588-2.372-10.103.543-19.017 6.51c-8.914 5.969-14.853 12.73-13.264 15.103c1.143 1.708 5.875.676 11.761-2.262");
}

</style>
