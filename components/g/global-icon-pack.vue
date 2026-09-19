<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="ndmxwl9el"/><path class="gxonlsbqd"/><path class="hl68-uair"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:global-icon-pack" /></template>
<style>
.gxonlsbqd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.931 23.427h36.132m-24.434-6.385c.256-1.023-.27-1.853-1.175-1.853s-1.846.83-2.102 1.853s.27 1.854 1.175 1.854s1.846-.83 2.102-1.854m-1.638-8.02L13.117 4.5m22.765 18.93v6.833c0 3.78-3.078 6.858-6.858 6.858H18.972c-3.78 0-6.859-3.078-6.859-6.858v-6.834");
}

.hl68-uair {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.05 23.43v6.833a3.025 3.025 0 0 1-3.026 3.027H18.972a3.025 3.025 0 0 1-3.027-3.027v-6.834m14.421-6.387c-.256-1.023.27-1.853 1.175-1.853s1.845.83 2.101 1.853s-.27 1.854-1.175 1.854s-1.845-.83-2.101-1.854m1.638-8.02L34.878 4.5");
}

.ndmxwl9el {
  cx: 24px;
  cy: 25.332px;
  r: 18.168px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
