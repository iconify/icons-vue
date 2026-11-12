<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="cmdh2s27t"/><path class="hmaaxbbaz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:head-heart-bulk-sharp" /></template>
<style>
.cmdh2s27t {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 21v-2.481C3.211 16.45 2.001 13.41 2 10c.001-4.551 3.449-7.999 8-8c2.136 0 4.189.775 5.707 2.293c1.428 1.428 2.211 3.357 2.287 5.365L20.8 13.4A.999.999 0 0 1 20 15h-2v3a1 1 0 0 1-1 1h-3v2a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1");
}

.cuyn6tgcc {
  fill: currentColor;
}

.hmaaxbbaz {
  d: path("M10 13.719q.673-.559 1.293-1.176c.455-.455.892-.936 1.25-1.473c.19-.285.457-.715.457-1.07c0-.627-.216-.965-.876-.883a1.6 1.6 0 0 0-.84.37c-.15.131-.284.305-.284.513a1 1 0 0 1-2 0c0-.208-.134-.382-.284-.513a1.6 1.6 0 0 0-.84-.37C7.216 9.035 7 9.373 7 10c0 .355.267.785.457 1.07c.358.537.795 1.018 1.25 1.473q.62.617 1.293 1.176m0-5.766a3.6 3.6 0 0 1 1.876-.82c1.216-.152 2.375.369 2.872 1.531c.18.421.252.88.252 1.336c-.001 1.465-1.321 2.985-2.293 3.957A21 21 0 0 1 10.6 15.8a1 1 0 0 1-1.2 0a21 21 0 0 1-2.107-1.843C6.321 12.985 5.001 11.465 5 10c0-.456.072-.915.252-1.336c.497-1.162 1.656-1.683 2.872-1.531a3.6 3.6 0 0 1 1.876.82");
}

</style>
