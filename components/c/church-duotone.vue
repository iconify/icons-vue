<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="fd7pxll7l"/><path class="p2uayccez"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:church-duotone" /></template>
<style>
.fd7pxll7l {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 12.382V11c0-.265.105-.52.293-.707l4-4a.997.997 0 0 1 1.414 0l4 4A1 1 0 0 1 17 11v1.382l1.447.724c1.075.537 2.552 1.546 2.553 2.894v3a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3v-3c.001-1.348 1.478-2.357 2.553-2.894Z");
}

.ft5dv1b6b {
  fill: none;
}

.p2uayccez {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 21V11l4-4l4 4v10m-8-8l-2 1c-1.226.613-2 1.387-2 2v3a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2v-3c0-.613-.774-1.387-2-2l-2-1M12 3v4m-2-2h4");
}

</style>
