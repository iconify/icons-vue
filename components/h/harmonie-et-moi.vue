<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b4jzqzass"/><path class="w28logklp"/><path class="zpluvobqc"/><path class="yp8ug4bup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:harmonie-et-moi" /></template>
<style>
.b4jzqzass {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.608 18.141l10.536-6.199l10.247 6.199v11.6l-10.397 6.316l-10.386-6.315z");
}

.w28logklp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.333 14.048L24.25 3.5l17.417 10.548v19.706L23.994 44.5L6.334 33.754z");
}

.yp8ug4bup {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.248 3.789l-.104 8.153l-8.916-3.1l-1.62 9.299");
}

.zpluvobqc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m41.666 14.048l-7.275 4.093l-1.665-9.426l-8.582 3.227m17.522 21.812l-7.275-4.012l7.275-5.736l-7.147-5.864M23.994 44.5v-8.443l8.616 3.018l1.781-9.333M6.333 33.754l7.275-4.012l1.272 9.136l9.114-2.821M6.333 14.047l7.275 4.094l-7.194 5.864l7.194 5.737");
}

</style>
