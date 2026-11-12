<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="a56rl2adt"/><path class="i70ycpbya"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:layer-arrow-down-broken" /></template>
<style>
.a56rl2adt {
  d: path("M4.9788 6.3149C2.9929 7.1093 2 7.5065 2 8C2 8.4935 2.9929 8.8907 4.9788 9.6851L7.7873 10.8085L7.78814 10.8088C9.77348 11.6029 10.7663 12 12 12C13.2337 12 14.2265 11.6029 16.2119 10.8088L16.2127 10.8085L19.0212 9.6851C21.0071 8.8907 22 8.4935 22 8C22 7.5065 21.0071 7.1093 19.0212 6.3149L16.2127 5.1915L16.2119 5.19116C14.2265 4.39709 13.2337 4 12 4C11.0461 4 10.2361 4.2374 9 4.7122");
}

.i70ycpbya {
  stroke-linejoin: round;
  d: path("M12 12V20M9 17L12 20L15 17");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
