<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="u_jws5mzq"/><path class="hfuoeu79m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:lipstick-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hfuoeu79m {
  d: path("M7 12L7 8.5007L7 2.0013C7 1.449 7.4477 1.0013 8 1.0013C8.1338 1.0013 8.2663 1.0282 8.3896 1.0803L16.3896 4.464C16.7596 4.6205 17 4.9832 17 5.385L17 12Z");
}

.u_jws5mzq {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 8.5007L7 2.0013C7 1.449 7.4477 1.0013 8 1.0013C8.1338 1.0013 8.2663 1.0282 8.3896 1.0803L16.3896 4.464C16.7596 4.6205 17 4.9832 17 5.385L17 14L18 14C18.5523 14 19 14.4477 19 15L19 22C19 22.5523 18.5523 23 18 23L6 23C5.4477 23 5 22.5523 5 22L5 15C5 14.4477 5.4477 14 6 14L7 14Z");
}

</style>
