<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e_c3hrbxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:coursera" /></template>
<style>
.e_c3hrbxx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.002 30.026c-2.067 3.085-5.577 4.942-9.34 4.942c-6.173 0-11.178-4.91-11.178-10.968s5.005-10.968 11.178-10.968c3.762 0 7.272 1.857 9.34 4.94l9.233-5.364C40.234 6.32 33.215 2.5 25.662 2.5C13.568 2.5 3.763 12.126 3.763 24s9.805 21.5 21.9 21.5c7.553 0 14.573-3.822 18.574-10.112z");
}

</style>
