<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h9xqq_bly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gem" /></template>
<style>
.h9xqq_bly {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.4458 3L15.5542 3C16.1529 3 16.7202 3.2683 17.1001 3.7311L21.5459 9.1475C21.8395 9.5052 22 9.9536 22 10.4164C22 10.9225 21.8081 11.4098 21.4631 11.78L13.4631 20.3636C13.0848 20.7695 12.5549 21 12 21C11.4451 21 10.9152 20.7695 10.5369 20.3636L2.5369 11.78C2.1919 11.4098 2 10.9225 2 10.4164C2 9.9536 2.1605 9.5052 2.4541 9.1475L6.8999 3.7311C7.2798 3.2683 7.8471 3 8.4458 3ZM2 10.4164L22 10.4164M7.5908 3.192L12 10.4164L16.4092 3.192");
}

</style>
