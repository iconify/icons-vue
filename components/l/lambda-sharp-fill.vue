<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uia271dsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:lambda-sharp-fill" /></template>
<style>
.uia271dsj {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4.9767 6.5L4.9767 5.5C4.9767 4.1193 6.096 3 7.4767 3C8.6115 3 9.604 3.7644 9.8938 4.8616L13.1987 17.3749C13.9329 20.1546 17.7787 20.4095 18.8733 17.7511L19.2317 16.8808M11.515 11L4.6807 21.4528");
}

</style>
