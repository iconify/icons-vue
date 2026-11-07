<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="skjes-bvt"/><path class="y-6rnrtnp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:face-smile-plus-corner-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.skjes-bvt {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M15.041 3.364a5 5 0 0 0 1.423 4.172a5 5 0 0 0 4.172 1.423a1 1 0 0 1 1.101.765a10 10 0 0 1-3.297 9.926a9.98 9.98 0 0 1-10.333 1.564A10 10 0 0 1 5.786 4.165A9.9 9.9 0 0 1 9.711 2.26a9.85 9.85 0 0 1 4.565.003a1 1 0 0 1 .765 1.101");
}

.y-6rnrtnp {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.049 3.236C8.403 1.916 3 6.202 3 12a9 9 0 0 0 9 9c5.798 0 10.084-5.403 8.764-11.049M9 9h.01M15 9h.01M8 14a5.657 5.657 0 0 0 8 0m2-10h4m-2-2v4");
}

</style>
