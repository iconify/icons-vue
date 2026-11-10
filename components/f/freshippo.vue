<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qzt05g53t"/><path class="gu-8u08ep"/><path class="wjrb41bvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:freshippo" /></template>
<style>
.gu-8u08ep {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.712 39.628c5.755 0 9.609-5.112 9.609-9.662c0-4.737-3.854-9.662-9.61-9.662c-6.115 0-4.91 2.947-9.711 2.947s-3.596-2.947-9.712-2.947c-5.755 0-9.609 4.925-9.609 9.662c0 4.55 3.854 9.662 9.61 9.662c6.115 0 4.91-2.946 9.711-2.946s3.596 2.946 9.712 2.946");
}

.qzt05g53t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m38.832 21.802l-3.04-10.44c2.975-.96 2.762-3.703 1.548-6.067c-.88-1.711-3.858.33-5.379 2.779c-1.811-.831-3.67-1.311-7.958-1.311s-6.147.48-7.959 1.31c-1.52-2.449-4.499-4.49-5.378-2.778c-1.214 2.364-1.428 5.107 1.547 6.067l-3.04 10.44");
}

.wjrb41bvh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.234 38.963c-2.688 2.703-7.747 4.375-13.234 4.375c-5.486 0-10.546-1.672-13.234-4.375m7.542-24.913v2.078m11.384-2.078v2.078");
}

</style>
