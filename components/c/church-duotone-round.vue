<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pn6msvbxq"/><path class="k3zfj-93j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:church-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.k3zfj-93j {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 21v-9c0-.64.36-1.36 1-2l3-3l3 3c.64.64 1 1.36 1 2v9m-8-8l-2 1c-1.226.613-2 1.387-2 2v2a3 3 0 0 0 3 3h10a3 3 0 0 0 3-3v-2c0-.613-.774-1.387-2-2l-2-1M12 3v4m-2-2h4");
}

.pn6msvbxq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 12.382V12c0-1.039.578-1.992 1.293-2.707l3-3a.997.997 0 0 1 1.414 0l3 3C16.422 10.008 17 10.961 17 12v.382l1.447.724c1.075.537 2.552 1.546 2.553 2.894v2a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4v-2c.001-1.348 1.478-2.357 2.553-2.894Z");
}

</style>
