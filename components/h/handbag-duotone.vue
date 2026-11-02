<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wnw3sybvv"/><path class="z2hiwsnbi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:handbag-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.wnw3sybvv {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17 7c1.608 0 2.801 1.348 2.992 2.876l1 8c.121.968-.116 2.126-.925 2.752A1.75 1.75 0 0 1 19 21H5c-.389 0-.759-.135-1.067-.372c-.809-.626-1.046-1.784-.925-2.752l1-8C4.199 8.348 5.392 7 7 7Z");
}

.z2hiwsnbi {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 8h5c1 0 1.857.857 2 2l1 8c.133 1.062-.336 2-1 2H5c-.664 0-1.133-.938-1-2l1-8c.143-1.143 1-2 2-2zM8 8a4 4 0 1 1 8 0");
}

</style>
