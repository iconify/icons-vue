<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e6lx6mbyt"/><circle class="xhudlzobb"/><path class="rstcmccof"/><path class="xm17ymb-l"/><path class="jdmpf6qsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:benefit-plus" /></template>
<style>
.e6lx6mbyt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.966 31.077c.335.28.696.41 1.507.41h.412c.669 0 1.211-.544 1.211-1.215h0c0-.67-.542-1.214-1.211-1.214h-.823a1.214 1.214 0 0 1-1.212-1.214h0c0-.671.543-1.215 1.212-1.215h.411c.812 0 1.173.13 1.508.41");
}

.jdmpf6qsw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.4 15.632v5.453c0 .506.41.916.917.916h.275m-2.154-4.857h1.925M9.702 19.023c0-1.013.821-1.833 1.833-1.833h0c1.013 0 1.833.82 1.833 1.833v1.19c0 1.013-.82 1.834-1.833 1.834h0a1.833 1.833 0 0 1-1.833-1.833m0 1.833v-7.332m22.885 7.332v-6.049c0-.708.574-1.283 1.283-1.283h0M31.5 17.19h2.566");
}

.rstcmccof {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.753 17.144v4.857m-7.301 4.679v3.025c0 1.012.82 1.833 1.833 1.833h0a1.833 1.833 0 0 0 1.833-1.833V26.68m0 3.025v1.833m-6.114-7.2v6.415c0 .507.41.917.917.917h.275m-6.839-2.2c0 1.013.821 1.833 1.833 1.833h0c1.013 0 1.833-.82 1.833-1.833v-1.19c0-1.012-.82-1.833-1.833-1.833h0c-1.012 0-1.833.82-1.833 1.833m0-1.834v7.332m4.282-11.731v-3.024c0-1.013-.82-1.833-1.833-1.833h0c-1.012 0-1.833.82-1.833 1.833m0 3.015v-4.857m-2.175 3.941a1.83 1.83 0 0 1-1.593.925h0a1.833 1.833 0 0 1-1.833-1.833v-1.191c0-1.013.82-1.833 1.833-1.833h0c1.012 0 1.833.82 1.833 1.833v.595h-3.666m14.653 1.504c-.315.552-.91.925-1.592.925h0a1.833 1.833 0 0 1-1.833-1.833v-1.191c0-1.013.82-1.833 1.833-1.833h0c1.012 0 1.833.82 1.833 1.833v.595H26.6");
}

.xhudlzobb {
  cx: 35.753px;
  cy: 14.898px;
  r: 0.75px;
  fill: currentColor;
}

.xm17ymb-l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M3.564 17.69c4.486 18.266 39.268 36.388 40.91.542C45.734 4.511 1.6 8.077 3.564 17.69");
}

</style>
