<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="z4ix8dbyc"/><path class="v3l0v53tm"/></g><path class="h7levef-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:drom-auto" /></template>
<style>
.h7levef-p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.215 27.066s-.29-4.614-.048-7.292c.145-1.607.637-2.098 1.851-2.457c2.635-.78 9.843-.095 9.843-.095m3.066 2.407c.325 1.779.914 3.13 2.284 3.434l2.418.538c2.459.546 1.89 2.268 1.603 4.124m-11.915.257c0 1.665-1.354 3.015-3.025 3.015s-3.026-1.35-3.026-3.015s1.355-3.015 3.026-3.015s3.025 1.35 3.025 3.015m8.716.453a2.52 2.52 0 0 1-2.527 2.518a2.52 2.52 0 0 1-2.527-2.518a2.52 2.52 0 0 1 2.527-2.518a2.52 2.52 0 0 1 2.527 2.518");
}

.v3l0v53tm {
  d: path("M4.5 21.688c4.07-4.222 10.56-1.764 9.429 5.34");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z4ix8dbyc {
  d: path("M12.742 27.5c2.723-1.315 6.014-.982 6.884 3.557");
}

</style>
