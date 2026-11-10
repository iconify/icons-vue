<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v45h1ub5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:heart-zap-sharp" /></template>
<style>
.v45h1ub5h {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.664 3.11L14 3.34C13.284 3.6 12.616 3.99 12 4.5C10.843 3.55 9.5 3 8 3C4.686 3 2 5.57 2 8.75C2 13.75 7.438 17.1 12 21C15.145 18.31 18.705 15.89 20.614 13L20.911 12.55M21.293 2.71L18 6H22L18.707 9.29");
}

</style>
