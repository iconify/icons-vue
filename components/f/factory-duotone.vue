<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="qffhruy4i"/><path class="b-h8y0i0i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:factory-duotone" /></template>
<style>
.b-h8y0i0i {
  d: path("M116 176a8 8 0 0 1-8 8H80a8 8 0 0 1 0-16h28a8 8 0 0 1 8 8m60-8h-28a8 8 0 0 0 0 16h28a8 8 0 0 0 0-16m64 48a8 8 0 0 1-8 8H24a8 8 0 0 1 0-16h8V88a8 8 0 0 1 12.8-6.4L96 120V88a8 8 0 0 1 12.8-6.4l38.74 29.05l11.56-80.91A16.08 16.08 0 0 1 174.94 16h18.12a16.08 16.08 0 0 1 15.84 13.74l15 105.13s.08.78.08 1.13v72h8a8 8 0 0 1 8.02 8m-77.86-94.4l8.53 6.4h36.11l-13.72-96h-18.12ZM48 208h160v-64h-40a8 8 0 0 1-4.8-1.6l-14.4-10.8L112 104v32a8 8 0 0 1-12.8 6.4L48 104Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.qffhruy4i {
  d: path("M216 136v80H40V88l64 48V88l64 48Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
