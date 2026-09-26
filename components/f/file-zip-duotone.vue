<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xxcb1mbaj"/><path class="fueq1pb7y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-zip-duotone" /></template>
<style>
.fueq1pb7y {
  d: path("M20 8L14 2M14 2L14 5C14 6.6569 15.3431 8 17 8L20 8M10 2L10 6M10 10L10 14M12 16C12 17.1046 11.1046 18 10 18C8.8954 18 8 17.1046 8 16C8 14.8954 8.8954 14 10 14C11.1046 14 12 14.8954 12 16Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xxcb1mbaj {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14 1C14.2652 1 14.5195 1.1054 14.707 1.293L20.707 7.293C20.8946 7.4805 21 7.7348 21 8V18C21 20.7614 18.7614 23 16 23H8C5.2386 23 3 20.7614 3 18V6C3 3.2386 5.2386 1 8 1H14Z");
  stroke: none;
}

</style>
