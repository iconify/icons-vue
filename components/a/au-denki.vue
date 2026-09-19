<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xsi4x_ywi"/><path class="aukuub-qe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:au-denki" /></template>
<style>
.aukuub-qe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m36 20.002l-2.5 4h-19l-2.5-4zm-21.5 4v6.5a5.71 5.71 0 0 0 3.759 5.367l1.74.633v3h8v-3l1.741-.633a5.71 5.71 0 0 0 3.76-5.367v-6.5");
}

.xsi4x_ywi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 39.502v6c-10.79 0-19.909-7.997-21.317-18.694S8.013 6.027 18.434 3.234c10.422-2.793 21.3 2.572 25.428 12.54c4.13 9.968.23 21.453-9.113 26.847M19 10.502v9.5m10.5-9.5v9.5");
}

</style>
