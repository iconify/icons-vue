<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o4v_zdbcb"/><path class="j6_xetb6q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:deposit-slip-scan" /></template>
<style>
.j6_xetb6q {
  d: path("M8 9h8v3.5H8Zm0 7h4m-9.5-1.75h19");
}

.o4v_zdbcb {
  d: path("M5 2.5h14v19H5ZM8 6h8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
