<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rarthkb1t"/><path class="n2tsp6jdg"/><path class="y3ub5xbtj"/><path class="iw1664brv"/><path class="d6wlhcbhs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lat" /></template>
<style>
.d6wlhcbhs {
  fill: var(--svg-color--e30065, #e30065);
  d: path("M3 18.75h2.25V21H3z");
}

.ft5dv1b6b {
  fill: none;
}

.iw1664brv {
  fill: var(--svg-color--00b6de, #00b6de);
  d: path("M18.75 3H21v2.25h-2.25z");
}

.n2tsp6jdg {
  fill: var(--svg-color--050505, #050505);
  d: path("M7.5 18.75V16.5h9v-9h2.25v9.478c0 .978-.83 1.772-1.855 1.772z");
}

.rarthkb1t {
  fill: var(--svg-color--050505, #050505);
  d: path("M7.105 5.25c-1.024 0-1.855.793-1.855 1.772V16.5H7.5v-9h9V5.25z");
}

.y3ub5xbtj {
  fill: var(--svg-color--f8bd00, #f8bd00);
  d: path("M9.75 9.75h4.5v4.5h-4.5z");
}

</style>
