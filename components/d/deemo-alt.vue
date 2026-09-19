<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="icojp1pxm"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:deemo-alt" /></template>
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

.icojp1pxm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.29 28.75c-5.03-.776-9.937 4.711-4.709 8.288c3.442 1.259 6.103-.223 7.468-2.433c.68-1.1.91-2.42.817-3.71l-.803-11.112c1.815 1.363 3.144 3 4.466 4.64l1.036-3.504c-2.016-.765-3.946-1.863-5.591-4.054c-.412-1.113-.269-1.817-.274-2.631c1.204.764 2.863 2.821 4.492 4.792l1.467-3.144c-2.19-.87-4.376-1.647-6.564-5.382c-.5.634-1.926 1.09-3.271 1.562c1.108 2.102 1.732 4.067 1.707 5.297z");
}

</style>
