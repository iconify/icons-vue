<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fes5aeb-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:grid-2x2-plus" /></template>
<style>
.fes5aeb-b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 11H18C19.1046 11 20 10.1046 20 9V5C20 3.3431 18.6569 2 17 2H5C3.3431 2 2 3.3431 2 5V17C2 18.6569 3.3431 20 5 20H9C10.1046 20 11 19.1046 11 18V2M19 16L19 22M16 19L22 19");
}

</style>
