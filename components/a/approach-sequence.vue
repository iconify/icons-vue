<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n7v1d2b8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:approach-sequence" /></template>
<style>
.n7v1d2b8l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m15.324 13.728l-2.355-.123l-2.048-1.434l-5.796 1.74l-1.229-.86l4.568-2.601l-2.867-2.007l-1.884.512l-.615-.431l1.987-1.965l1.168-2.54l.614.43l.164 1.946l2.867 2.007l.881-5.181l1.229.86l.347 6.042l2.048 1.434ZM9 20.5h12.5");
}

</style>
