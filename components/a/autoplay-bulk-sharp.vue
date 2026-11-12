<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ztr1bmequ"/><path class="cylnd1-sq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:autoplay-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.cylnd1-sq {
  d: path("M9 8a1 1 0 0 1 1.555-.832l6 4a1 1 0 0 1 0 1.664l-6 4A1 1 0 0 1 9 16Z");
}

.ztr1bmequ {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 4.937V4a1 1 0 0 1 2 0v4a.997.997 0 0 1-1 1h-4a1 1 0 0 1 0-2h2.174a7.944 7.944 0 0 0-13.711 7.512a7.945 7.945 0 0 0 14.643 1.041a.999.999 0 1 1 1.788.894a9.94 9.94 0 0 1-7.688 5.423a9.94 9.94 0 0 1-8.766-3.406a9.947 9.947 0 0 1 .792-13.751A9.94 9.94 0 0 1 19 4.937m-2.445 6.231a1 1 0 0 1 0 1.664l-6 4A1 1 0 0 1 9 16V8a1 1 0 0 1 1.555-.832Z");
}

</style>
