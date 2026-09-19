<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qdx-_vf3r"/><path class="ibug3ib-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:eset-payment-protection" /></template>
<style>
.ibug3ib-n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.488 41.6c4.337-1.495 7.428-4.97 7.913-9.394c.19-1.739.065-4.308-.034-5.767a1.22 1.22 0 0 0-1.184-1.135c-1.962-.06-4.242-.388-6.004-2.123a.984.984 0 0 0-1.381 0c-1.763 1.735-4.043 2.062-6.004 2.123a1.22 1.22 0 0 0-1.184 1.135c-.1 1.46-.225 4.028-.034 5.767c.485 4.424 3.576 7.9 7.912 9.394m0 0V22.897");
}

.qdx-_vf3r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 25.27V12.4a4 4 0 0 0-4-4h-31a4 4 0 0 0-4 4v23.2a4 4 0 0 0 4 4h25.265M4.5 15.636h39");
}

</style>
