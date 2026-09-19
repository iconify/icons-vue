<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g2wj9jbhp"/><path class="vb_azf7dy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:krungsri-kept" /></template>
<style>
.g2wj9jbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

.vb_azf7dy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.05 19.858v7.6c0 .705.567 1.276 1.266 1.276h.38m-2.976-6.768h2.66m-12.752 5.479a2.53 2.53 0 0 1-2.2 1.29h0a2.543 2.543 0 0 1-2.532-2.554V24.52a2.543 2.543 0 0 1 2.532-2.554h0a2.543 2.543 0 0 1 2.532 2.554h0v.83h-5.064m7.814.83a2.543 2.543 0 0 0 2.532 2.554h0a2.543 2.543 0 0 0 2.532-2.554h0v-1.66a2.543 2.543 0 0 0-2.532-2.554h0a2.543 2.543 0 0 0-2.532 2.554h0m0-2.554v10.217M11.304 18.517v10.217m0-3.558l5.445-6.624m0 10.182l-4.17-5.108");
}

</style>
