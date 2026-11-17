<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t7zu9hv_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-connection-round" /></template>
<style>
.t7zu9hv_c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 17H8.778a3 3 0 0 1-3-3V9.806a3 3 0 0 1 1.024-2.258l3.222-2.82a3 3 0 0 1 3.952 0l3.222 2.82a3 3 0 0 1 1.024 2.258V14a3 3 0 0 1-3 3zm0 0v4m-8 0h16");
}

</style>
