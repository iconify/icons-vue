<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wl-qb8beg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:evie" /></template>
<style>
.wl-qb8beg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.51a21.5 21.5 0 0 0-12.61 38.92c.44-10 .83-20 3-29.12c1.23.75 2.35 2.25 3.79 2.63a7.4 7.4 0 0 1 .53-2.53c1.77 1.1 4.26 3.56 6 3.25a22.6 22.6 0 0 1 10.37.44c1.38 8.72-2.62 12.65-7.49 15.82c4.68.67 8.43 3.5 11.89 7A21.5 21.5 0 0 0 24 2.51m.34 17.43a2.24 2.24 0 1 0 2.27 2.23a2.23 2.23 0 0 0-2.27-2.23m0 0");
}

</style>
