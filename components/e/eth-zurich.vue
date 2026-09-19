<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fy102_bnr"/><path class="g2wj9jbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:eth-zurich" /></template>
<style>
.fy102_bnr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.943 18.128h10.276M22.01 29.872l2.071-11.744m5.138 0l-2.071 11.744M37 18.128l-2.071 11.744m-6.741-5.894h7.78M12.035 24h3.829m1.008 5.872H11l2.071-11.744h5.872");
}

.g2wj9jbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

</style>
