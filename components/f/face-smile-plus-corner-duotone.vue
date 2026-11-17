<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="f6-m5qp7h"/><path class="y-6rnrtnp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:face-smile-plus-corner-duotone" /></template>
<style>
.f6-m5qp7h {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M14.049 3.236a6 6 0 0 0 6.715 6.715a9.002 9.002 0 0 1-15.128 8.413a9.001 9.001 0 0 1 8.413-15.128");
}

.ft5dv1b6b {
  fill: none;
}

.y-6rnrtnp {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.049 3.236C8.403 1.916 3 6.202 3 12a9 9 0 0 0 9 9c5.798 0 10.084-5.403 8.764-11.049M9 9h.01M15 9h.01M8 14a5.657 5.657 0 0 0 8 0m2-10h4m-2-2v4");
}

</style>
