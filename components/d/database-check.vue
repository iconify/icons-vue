<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o8uitvbxl"/><path class="tu5a1ha0j"/><path class="qyzgraclp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:database-check" /></template>
<style>
.o8uitvbxl {
  d: path("M13.923 21.168c-.617.054-1.261.082-1.923.082c-4.4 0-8-1.25-8-2.75v-13C4 4 7.6 2.75 12 2.75S20 4 20 5.5v7.355");
}

.qyzgraclp {
  d: path("M4 5.5C4 7 7.6 8.25 12 8.25S20 7 20 5.5M4 12c0 1.2 2.3 2.2 5.5 2.5m5.25 3.5l2 2L21 15.75");
}

.tu5a1ha0j {
  d: path("M4 5.5C4 7 7.6 8.25 12 8.25S20 7 20 5.5M4 12c0 1.5 3.6 2.75 8 2.75c.743 0 1.463-.036 2.147-.102m1.033-.128C18.01 14.093 20 13.115 20 12");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
