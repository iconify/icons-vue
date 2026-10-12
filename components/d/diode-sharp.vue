<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_3z_qbkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:diode-sharp" /></template>
<style>
.v_3z_qbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 12H7.5m8.5 0h5.25M7.5 7.5v10l.85-.52l7.3-4.46l.85-.52l-.85-.52l-7.3-4.46l-.85-.52zm8.5-1v11");
}

</style>
