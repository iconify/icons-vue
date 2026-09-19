<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fsyp04b4g"/><path class="jxbonkb4m"/><path class="ry5vhfqtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:adpmobile" /></template>
<style>
.fsyp04b4g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.56 19.478v5.087h-4.946");
}

.jxbonkb4m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.848 28.24h6.712v4.309h5.193a7.95 7.95 0 0 0 7.173-4.522h.775v4.522h4.027v-4.027h1.237a6.535 6.535 0 0 0 6.535-6.536h0a6.535 6.535 0 0 0-6.535-6.535H31.7v8.408a8.41 8.41 0 0 0-8.407-8.408h-8.832L4.5 32.549h4.981z");
}

.ry5vhfqtd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.951 28.24h1.413a4.38 4.38 0 0 0 4.38-4.381h0a4.38 4.38 0 0 0-4.38-4.38h-1.413m13.853 4.686h1.664a2.343 2.343 0 0 0 2.343-2.343h0a2.343 2.343 0 0 0-2.343-2.344h-1.664");
}

</style>
