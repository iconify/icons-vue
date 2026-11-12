<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u29u3ubqq"/><path class="egbjf6-8b"/><path class="by1hc2n7w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:braces-broken" /></template>
<style>
.by1hc2n7w {
  d: path("M14.2076 2C17.9456 2 18.551 5.16122 18.5642 6.75357C18.5642 8.94929 20.1049 10.3293 21.5547 11.2505C22.1604 11.6353 22.1524 12.3721 21.5049 12.7089C20.0546 13.6294 18.5134 15.0085 18.5134 17.2027C18.5002 18.794 17.8945 22 14.1553 22");
}

.egbjf6-8b {
  d: path("M5.6748 5.02892C6.09191 3.55204 7.17309 2 9.79224 2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u29u3ubqq {
  d: path("M9.84465 22.039C6.10551 22.039 5.49981 18.833 5.48664 17.2417C5.48664 15.0475 3.94543 13.6684 2.49513 12.7479C1.84765 12.4111 1.83956 11.6743 2.44525 11.2895C3.31852 10.7346 4.22475 10.0133 4.80743 9.04761");
}

</style>
