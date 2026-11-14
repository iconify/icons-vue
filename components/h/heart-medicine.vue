<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tkg2a0ekb"/><path class="smp47eb-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:heart-medicine" /></template>
<style>
.smp47eb-k {
  d: path("m7.757 13.914l5.657-5.657l2.829 2.829l-5.657 5.657Zm2.829-2.828l2.828 2.828");
}

.tkg2a0ekb {
  d: path("M12 20c-6-4.5-9.5-7.5-9.5-11.5a5 5 0 0 1 9.5-2a5 5 0 0 1 9.5 2c0 4-3.5 7-9.5 11.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
