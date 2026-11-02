<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xvvptabed"/><path class="f2xx-dbsh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:church-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.f2xx-dbsh {
  d: path("M13 4h1a1 1 0 0 1 0 2h-1v.586l2.707 2.707C16.422 10.008 17 10.961 17 12v9a1 1 0 0 1-2 0v-9c0-.468-.395-.98-.707-1.293L12 8.414l-2.293 2.293C9.395 11.02 9 11.532 9 12v9a1 1 0 0 1-2 0v-9c0-1.039.578-1.992 1.293-2.707L11 6.586V6h-1a1 1 0 0 1 0-2h1V3a1 1 0 0 1 2 0Z");
}

.xvvptabed {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18.447 13.106c1.075.537 2.552 1.546 2.553 2.894v2a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4v-2c.001-1.348 1.478-2.357 2.553-2.894L7 12.382V12c0-1.039.578-1.992 1.293-2.707l3-3a.997.997 0 0 1 1.414 0l3 3C16.422 10.008 17 10.961 17 12v.382Z");
}

</style>
