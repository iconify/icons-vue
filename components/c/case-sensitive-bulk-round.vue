<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="o3-upxd0h"/><path class="pw95ckhck"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:case-sensitive-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.o3-upxd0h {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20.089 11.588A1 1 0 0 1 22 12v6a1 1 0 0 1-1.911.412a4.002 4.002 0 0 1-5.132-6.009a4 4 0 0 1 5.132-.815M20 15a2 2 0 1 0-3.999-.001A2 2 0 0 0 20 15");
}

.pw95ckhck {
  d: path("M6.051 5.684a1 1 0 0 1 1.898 0l4 12a1.001 1.001 0 0 1-1.898.632L8.946 15H5.054l-1.105 3.316a1.001 1.001 0 0 1-1.898-.632ZM8.279 13L7 9.162L5.721 13Z");
}

</style>
