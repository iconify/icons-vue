<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bpq75rn9q"/><path class="pw2hc_b3x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bell-ring-duotone-sharp" /></template>
<style>
.bpq75rn9q {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 20a1 1 0 0 1-1-1v-2c0-.39.098-.773.299-1.108c.133-.222.312-.417.494-.599c.065-.066.145-.133.193-.214C5 15.057 5 15.026 5 15v-4a7 7 0 1 1 14 0v4c0 .026 0 .057.014.079c.048.081.128.148.193.214c.182.182.361.377.494.599c.201.335.299.718.299 1.108v2a1 1 0 0 1-1 1h-4.171a3 3 0 0 1-5.658 0Z");
}

.ft5dv1b6b {
  fill: none;
}

.pw2hc_b3x {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 19H5v-2c0-1 1-1 1-2v-4a6 6 0 1 1 12 0v4c0 1 1 1 1 2v2zm-2 0a2 2 0 1 0 4 0m3-16a9.4 9.4 0 0 1 3 3M4 6a9.4 9.4 0 0 1 3-3");
}

</style>
