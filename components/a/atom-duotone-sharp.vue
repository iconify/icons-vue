<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="eu4i4cclu"/><path class="ey87q0beb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:atom-duotone-sharp" /></template>
<style>
.eu4i4cclu {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 19.157C8.722 21.122 5.566 21.566 4 20s-1.122-4.722.843-8C2.878 8.722 2.434 5.566 4 4s4.722-1.122 8 .843c3.278-1.965 6.434-2.409 8-.843s1.122 4.722-.843 8c1.965 3.278 2.409 6.434.843 8s-4.722 1.122-8-.843");
}

.ey87q0beb {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20 20c-2.21 2.21-7.582.418-12-4S1.79 6.21 4 4s7.582-.418 12 4s6.21 9.79 4 12m0-16c2.21 2.21.418 7.582-4 12s-9.79 6.21-12 4s-.418-7.582 4-12s9.79-6.21 12-4m-9 8a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

.ft5dv1b6b {
  fill: none;
}

</style>
