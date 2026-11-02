<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pxritnb7d"/><path class="zmtsjs1io"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:carrot-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.pxritnb7d {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M18.495 5.505c.836-.112 1.684.061 2.362.581c.529.406.892.977 1.095 1.608a1 1 0 0 1 0 .612c-.521 1.624-1.956 2.458-3.615 2.165a5.3 5.3 0 0 1-2.89 5.423l-12 6a1 1 0 0 1-1.341-1.341l6-12a5.3 5.3 0 0 1 5.423-2.89c-.293-1.659.541-3.094 2.165-3.615a1 1 0 0 1 .612 0c.631.203 1.202.566 1.608 1.095c.52.678.693 1.526.581 2.362");
}

.zmtsjs1io {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 21L9 9c1.343-2.687 4.958-3.203 7-1c2.203 2.042 1.687 5.657-1 7Zm5-10l2 1m1 5l-2-1m7-13c-1.948.625-2.125 2.917 0 5c2.125-2.083 1.948-4.375 0-5m5 5c-.625 1.948-2.917 2.125-5 0c2.083-2.125 4.375-1.948 5 0m-5 0h.01");
}

</style>
