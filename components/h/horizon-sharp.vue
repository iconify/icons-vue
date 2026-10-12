<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ddv4-1hmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:horizon-sharp" /></template>
<style>
.ddv4-1hmq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 10.5h18.5m-9.25 0L4.5 21.25M12 10.5l7.5 10.75m-7.5-7v1.5m0 2.5v3");
}

</style>
