<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="kwwnm_5ft"/><path class="la-33bykb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:coffee-to-go-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.kwwnm_5ft {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5.073 7.921c-.746-.162-1.314-.682-1.267-1.487c.02-.328.151-.641.319-.92l.981-1.961c.468-.937 1.09-1.449 2.15-1.534C7.503 1.999 7.752 2 8 2h8c.248 0 .497-.001.744.019c1.06.085 1.682.597 2.15 1.534l.981 1.961c.168.279.299.592.319.92c.047.805-.521 1.325-1.267 1.487l-.93 11.162c-.064.762-.327 1.504-.865 2.061c-.562.583-1.331.856-2.132.856H9c-.801 0-1.57-.273-2.132-.856c-.538-.557-.801-1.299-.865-2.061Z");
}

.la-33bykb {
  d: path("M17 11a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2Zm0 4a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2Z");
}

</style>
