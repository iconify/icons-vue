<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="upa9ttzvv"/><path class="mrdeqqbpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:krungsri-access-mobile" /></template>
<style>
.mrdeqqbpx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.043 16.054c-3.388-.485-5.905 3.02-7.146 5.454c-1.723 3.38-1.937 6.936.72 7.293c2.096.281 3.779-.15 6.861-3.91c.391-.477 1.21-1.513 2.161-3.79c.939-1.947-.246-4.711-2.596-5.047");
}

.upa9ttzvv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.628 21.126l-1.978 4.742c-.926 2.218.224 4.845 4.754 2.218c3.686-2.14 7.912-9.569 6.045-14.845c-1.22-3.45-4.4-4.567-7.896-4.789c-6.43-.408-11.547 2.527-14.35 5.637c-5.334 5.92-7.45 16.317.82 22.613c5.097 3.88 15.39 3.811 20.766 0c7.903-5.601 10.154-12.062 12.726-19.514l1.985 6.316m-20.872-7.171l-1.965 4.71m20.852-3.855l-5.713 3.623");
}

</style>
