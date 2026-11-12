<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xscxw-bfa"/><path class="ak-l-xbnm"/><path class="emel-ifwl"/><path class="c-y9gqbtc"/><path class="pdxc586_x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:grid-3x3-broken" /></template>
<style>
.ak-l-xbnm {
  d: path("M8.69579 2.05957L8.69531 18");
}

.c-y9gqbtc {
  d: path("M21.9492 8.68701L2.03679 8.68701");
}

.emel-ifwl {
  d: path("M15.3223 6.01309L15.3219 21.9714");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pdxc586_x {
  d: path("M21.9805 15.3135L2.03762 15.313");
}

.xscxw-bfa {
  d: path("M21.9954 10.0731C21.9685 6.61368 21.7852 4.71412 20.5355 3.46447C19.0711 2 16.714 2 12 2C7.28595 2 4.92893 2 3.46447 3.46447C2 4.92893 2 7.28595 2 12C2 16.714 2 19.0711 3.46447 20.5355C4.92893 22 7.28595 22 12 22C16.714 22 19.0711 22 20.5355 20.5355C21.7764 19.2947 21.9658 17.4131 21.9948 14");
}

</style>
