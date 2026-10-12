<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ag7ixhbdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:destination-sharp" /></template>
<style>
.ag7ixhbdb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 21.25V2.75m-3.25 18.5h6.5m-2.5-18.5h12l-.43.61l-2.14 3.03l-.43.61l.43.61l2.14 3.03l.43.61H8v-8.5z");
}

</style>
