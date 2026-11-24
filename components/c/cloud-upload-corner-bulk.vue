<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="cvy-xbymr"/><path class="nye7ypq7n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cloud-upload-corner-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.cvy-xbymr {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 20a6 6 0 0 1-.74-11.955c.742-2.012 2.206-3.704 4.274-4.403c2.856-.964 5.823.266 7.337 2.833c.419.717.721 1.496.896 2.307A.998.998 0 0 1 17.791 10H10a.997.997 0 0 0-1 1v8a1 1 0 0 1-1 1Z");
}

.nye7ypq7n {
  d: path("M18 15.414V21a1 1 0 0 1-2 0v-5.586l-1.293 1.293a.999.999 0 1 1-1.414-1.414l3-3a1 1 0 0 1 1.414 0l3 3a.999.999 0 1 1-1.414 1.414Z");
}

</style>
