<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="jl3n3_bjv"/><path class="gpsi6mbox"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:hockey-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gpsi6mbox {
  d: path("M224 152h-93.1L38.1 42.82a8 8 0 0 0-12.2 10.36l133.61 157.18A16 16 0 0 0 171.7 216H224a16 16 0 0 0 16-16v-32a16 16 0 0 0-16-16m-79.5 16H192v32h-20.3Zm79.5 32h-16v-32h16Zm-111.82-20.45a8 8 0 0 0-11.27.92L84.3 200H64v-32h21.2a8 8 0 0 0 0-16H32a16 16 0 0 0-16 16v32a16 16 0 0 0 16 16h52.3a16 16 0 0 0 12.19-5.64l16.61-19.53a8 8 0 0 0-.92-11.28M32 168h16v32H32Zm117.9-45.18l68-80a8 8 0 0 1 12.2 10.36l-68 80a8 8 0 1 1-12.2-10.36");
}

.jl3n3_bjv {
  d: path("M200 160v48h-28.3a8 8 0 0 1-6.1-2.82l-38-44.7l-37.2 44.64a8 8 0 0 1-6.15 2.88H56v-48z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
