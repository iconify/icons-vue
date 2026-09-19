<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b5t0irbpi"/><path class="r7e9cxhkl"/><path class="ohmxwjb6l"/><path class="ic68y9b3k"/><path class="zxyj18unb"/><circle class="l955eybyd"/><path class="yily-eb8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fdeai" /></template>
<style>
.b5t0irbpi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.736 13.723a5.079 5.079 0 1 1 5.08-5.079v5.08m-9.602 23.318a5.08 5.08 0 1 0 9.601 2.314v-5.08");
}

.ic68y9b3k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.921 18.179a5.08 5.08 0 0 0-4.618-8.913m-3.465 23.166a5.079 5.079 0 1 0 8.083-4.096");
}

.l955eybyd {
  cx: 24px;
  cy: 24px;
  r: 6.92px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ohmxwjb6l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.079 28.336a5.079 5.079 0 1 1 5.079-5.079m17.106-9.534a5.079 5.079 0 1 0-5.08-5.079v5.08m9.602 23.318a5.08 5.08 0 1 1-9.601 2.314v-5.08");
}

.r7e9cxhkl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.079 18.179a5.08 5.08 0 0 1 4.618-8.913m3.465 23.166a5.079 5.079 0 1 1-8.083-4.096");
}

.yily-eb8z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.025 20.05h3.95M22.025 24h2.568m-2.568-3.95v7.9");
}

.zxyj18unb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.921 28.336a5.079 5.079 0 1 0-5.079-5.079M17.73 21.076l-1.937-.903m16.414 7.654l-1.937-.903m-12.54 0l-1.937.903m16.414-7.654l-1.936.903m-3.347-3.346l.903-1.937m-7.654 16.414l.903-1.937m0-12.542l-.903-1.935m7.654 16.414l-.903-1.937");
}

</style>
