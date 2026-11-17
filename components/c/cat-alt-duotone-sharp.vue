<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bmxlpxbtn"/><path class="ot9k8kbpn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cat-alt-duotone-sharp" /></template>
<style>
.bmxlpxbtn {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 8V3a6.42 6.42 0 0 1 4 3c1.316-.3 2.684-.3 4 0a6.42 6.42 0 0 1 4-3v5c.5 1.6 1 3.5 1 6c0 1.152-.356 2.063-1 3c-1.384 1.915-3.651 2.999-6 3c-2.349-.001-4.616-1.085-6-3c-.644-.937-1-1.848-1-3c0-2.5.5-4.4 1-6");
}

.ft5dv1b6b {
  fill: none;
}

.ot9k8kbpn {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 20c-2.5 0-4.7-1.2-6-3c-.55-.8-1-1.7-1-3c0-2.5.5-4.4 1-6V3c2 .5 3.3 1.8 4 3c1.3-.3 2.7-.3 4 0c.7-1.2 2-2.5 4-3v5c.5 1.6 1 3.5 1 6c0 1.3-.45 2.2-1 3c-1.3 1.8-3.5 3-6 3m-9-7l4 1m-4 4l5-1m13-4l-4 1m4 4l-5-1m-7-6h.01M15 11h.01M11 14h2l-1 1Z");
}

</style>
