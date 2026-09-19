<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m8bt6z5bo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:favorites" /></template>
<style>
.m8bt6z5bo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m25.817 7.607l3.493 10.748h11.302c1.85 0 2.62 2.369 1.123 3.457l-9.144 6.643l3.493 10.749c.572 1.76-1.443 3.224-2.94 2.136L24 34.697l-9.143 6.643c-1.498 1.088-3.513-.376-2.94-2.136l3.492-10.749l-9.144-6.643c-1.497-1.088-.728-3.457 1.123-3.457H18.69l3.493-10.748c.572-1.76 3.062-1.76 3.634 0");
}

</style>
