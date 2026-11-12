<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="x1xlejbdu"/><path class="ru31h5b-o"/><path class="mi4udvb7f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:layers-arrow-down-broken" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mi4udvb7f {
  stroke-linejoin: round;
  d: path("M12 15V21M9 18L12 21L15 18");
}

.ru31h5b-o {
  d: path("M19.0212 12.6851C21.0071 11.8907 22 11.4935 22 11C22 10.5065 21.0071 10.1093 19.0212 9.3149L18.2339 9M5.7661 9L4.9788 9.3149C2.9929 10.1093 2 10.5065 2 11C2 11.4935 2.9929 11.8907 4.9788 12.6851L7.7873 13.8085L7.78814 13.8088C9.77348 14.6029 10.7663 15 12 15C12.9539 15 13.7639 14.7626 15 14.2878");
}

.x1xlejbdu {
  d: path("M4.9788 5.3149C2.9929 6.1093 2 6.5065 2 7C2 7.4935 2.9929 7.8907 4.9788 8.6851L7.7873 9.8085L7.78814 9.80884C9.77348 10.6029 10.7663 11 12 11C13.2337 11 14.2265 10.6029 16.2119 9.80884L16.2127 9.8085L19.0212 8.6851C21.0071 7.8907 22 7.4935 22 7C22 6.5065 21.0071 6.1093 19.0212 5.3149L16.2127 4.1915L16.2119 4.19116C14.2265 3.39709 13.2337 3 12 3C11.0461 3 10.2361 3.2374 9 3.7122");
}

</style>
