<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lia6c03rv"/><path class="tyqxlrbzk"/><path class="efke-wbwi"/><path class="lt87iveio"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:columns-4-line-duotone" /></template>
<style>
.efke-wbwi {
  d: path("M17 20.9651L17 3.03507");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lia6c03rv {
  d: path("M12 21L12 3");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.lt87iveio {
  d: path("M10 21H14C17.7712 21 19.6569 21 20.8284 19.8284C22 18.6569 22 16.7712 22 13V11C22 7.22876 22 5.34315 20.8284 4.17157C19.6569 3 17.7712 3 14 3H10C6.22876 3 4.34315 3 3.17157 4.17157C2 5.34315 2 7.22876 2 11V13C2 16.7712 2 18.6569 3.17157 19.8284C4.34315 21 6.22876 21 10 21Z");
}

.tyqxlrbzk {
  d: path("M7 20.965L7 3.03502");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
