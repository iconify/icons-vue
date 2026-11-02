<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qlgxuybus"/><path class="tm-7tqbxw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:eject-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.qlgxuybus {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m4.136 15.496l7-12a1 1 0 0 1 1.728 0l7 12A1.002 1.002 0 0 1 19 17H5a.998.998 0 0 1-.864-1.504");
}

.tm-7tqbxw {
  d: path("M5 19h14a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2");
}

</style>
