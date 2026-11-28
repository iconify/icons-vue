<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="abaekfnni"/><path clip-rule="evenodd" class="n26113bri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gradient-linear-sharp-duotone" /></template>
<style>
.abaekfnni {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 2H21C21.552 2 22 2.448 22 3V21C22 21.552 21.552 22 21 22H3C2.448 22 2 21.552 2 21V3C2 2.448 2.448 2 3 2H12Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.n26113bri {
  fill-rule: evenodd;
  d: path("M2 10.586L2.293 10.293L10.293 2.293L10.586 2H12H13.414L11.707 3.707L3.707 11.707L2 13.414V10.586ZM2 16.586L2.293 16.293L16.293 2.293L16.586 2H19.414L17.707 3.707L3.707 17.707L2 19.414V16.586ZM4.586 22L6.293 20.293L20.293 6.293L22 4.586V7.414L21.707 7.707L7.707 21.707L7.414 22H4.586Z");
}

</style>
