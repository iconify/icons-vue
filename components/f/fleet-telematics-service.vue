<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b__nxep4k"/><path class="s5on1cc-s"/><path class="x6bpwd-mz"/><path class="g2wj9jbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fleet-telematics-service" /></template>
<style>
.b__nxep4k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.286 25.654c1.74 0 3.152 1.416 3.152 3.163s-1.412 3.164-3.152 3.164a3.16 3.16 0 0 1-3.152-3.164v-.004a3.16 3.16 0 0 1 3.152-3.16");
}

.g2wj9jbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

.s5on1cc-s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.286 22.237c-3.618 0-6.551 2.944-6.551 6.576v.48c.265 3.602 3.244 6.5 6.55 10.249c3.453-3.914 6.552-6.878 6.552-10.73h0c0-3.63-2.933-6.575-6.551-6.575M27.842 8.458L24.4 16.57l-3.442-8.112L24.4 9.843z");
}

.x6bpwd-mz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.02 20.397c-8.01 3.322-16.958 8.219-23.44 14.37M24.4 16.57h17.614");
}

</style>
