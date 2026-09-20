<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ggiw2mp1b"/><path class="b2udj79yy"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:el-background" /></template>
<style>
.b2udj79yy {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.235 12.133L7 9.929v1.758l5.235 2.145l7.265-3.333v2.317l-7.265 3.307L7 13.919v1.672l5.235 2.167L19.5 14.49v2.166L12.235 20L4.5 16.846V6.622L12 4l7.5 2.622v2.204z");
}

.ft5dv1b6b {
  fill: none;
}

.ggiw2mp1b {
  fill: var(--svg-color--2c6190, #2c6190);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
