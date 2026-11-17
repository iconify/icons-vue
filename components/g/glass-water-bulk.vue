<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="pkgtjpbhu"/><path class="ah77tub-x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:glass-water-bulk" /></template>
<style>
.ah77tub-x {
  d: path("M6 11h12a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2");
}

.cuyn6tgcc {
  fill: currentColor;
}

.pkgtjpbhu {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m18.994 12.11l-.802 7.221A3 3 0 0 1 15.21 22H8.79a3 3 0 0 1-2.982-2.669L4.227 5.098A2.79 2.79 0 0 1 7 2h10a2.79 2.79 0 0 1 2.773 3.098Z");
}

</style>
