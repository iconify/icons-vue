<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="m_6h9kb1s"><path class="bt71u9lmt"/><path class="samryteff"/><path class="idnnmmb0j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:aniyomi" /></template>
<style>
.bt71u9lmt {
  d: path("M24 2.5c11.9 0 21.5 9.6 21.5 21.5S35.9 45.5 24 45.5S2.5 35.9 2.5 24S12.1 2.5 24 2.5");
}

.idnnmmb0j {
  d: path("M32.7 25.3c.7-.2 1.2-.9 1-1.6c-.1-.5-.5-.9-1-1l-13.6-7.8c-.7-.2-1.4.2-1.6.9c0 .1-.1.3-.1.5v15.6c0 .7.5 1.3 1.2 1.4c.2 0 .3 0 .5-.1z");
}

.m_6h9kb1s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 90;
}

.samryteff {
  d: path("M24 7c9.4 0 17 7.6 17 17s-7.6 17-17 17S7 33.4 7 24S14.6 7 24 7");
}

</style>
