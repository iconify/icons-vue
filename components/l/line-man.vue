<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x907k8bwq"/><path class="hbe4cz4jw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:line-man" /></template>
<style>
.hbe4cz4jw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.208 9.248v29.055c0 2.325-1.8 4.197-4.036 4.197s-4.035-1.872-4.035-4.197V19.276m-20.274 0v19.027c0 2.325-1.8 4.197-4.036 4.197s-4.035-1.872-4.035-4.197V9.248");
}

.x907k8bwq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.999 29.411l-5.706-5.706L7.06 12.474c-1.644-1.644-1.695-4.24-.114-5.82h0c1.58-1.58 4.176-1.53 5.82.113L23.998 18L35.233 6.767c1.645-1.644 4.24-1.695 5.822-.114h0c1.58 1.58 1.53 4.177-.115 5.82L29.707 23.709z");
}

</style>
