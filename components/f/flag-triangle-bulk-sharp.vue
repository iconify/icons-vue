<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="fiojrubzm"/><path class="kqrliobak"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flag-triangle-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.fiojrubzm {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m6.447 2.106l12 6a.998.998 0 0 1 0 1.788l-12 6A1 1 0 0 1 5 15V3a1 1 0 0 1 1.447-.894");
}

.kqrliobak {
  d: path("M7 21a1 1 0 0 1-2 0v-6a1 1 0 0 1 2 0Z");
}

</style>
