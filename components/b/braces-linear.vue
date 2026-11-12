<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="id_dkzbpx"/><path class="by1hc2n7w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:braces-linear" /></template>
<style>
.by1hc2n7w {
  d: path("M14.2076 2C17.9456 2 18.551 5.16122 18.5642 6.75357C18.5642 8.94929 20.1049 10.3293 21.5547 11.2505C22.1604 11.6353 22.1524 12.3721 21.5049 12.7089C20.0546 13.6294 18.5134 15.0085 18.5134 17.2027C18.5002 18.794 17.8945 22 14.1553 22");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.id_dkzbpx {
  d: path("M9.79237 2C6.0544 2 5.44899 5.16122 5.43582 6.75357C5.43582 8.94929 3.8951 10.3293 2.44525 11.2505C1.83956 11.6353 1.84765 12.3721 2.49513 12.7089C3.94543 13.6294 5.48664 15.0085 5.48664 17.2027C5.49981 18.794 6.10551 22 9.84465 22");
}

</style>
