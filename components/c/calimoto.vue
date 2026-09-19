<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="z9dynpl_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calimoto" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z9dynpl_n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.022 4.035c5.121 1.835 2.628 8.017-1.213 12.347c-6.543 7.377-4 15.505 2.736 17.369c5.26 1.456 14.21-4.83 10.62-14.738c-1.256-3.467-.896-6.639 1.503-7.395c2.288-.72 4.072 1.564 5.216 4.955c2.018 5.977 6.013 5.051 10.088 2.693");
}

</style>
