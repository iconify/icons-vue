<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m263k3bfd"/><path class="zs2qes99h"/><path class="fiw4jed-n"/><path class="ufhkwtqlu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-confetti-ball" /></template>
<style>
.fiw4jed-n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.126 33.26q.257.364.397.815c.472 1.553-.42 3.241-1.995 3.77m22.607-11.463c.279.099.547.243.795.435c1.285.995 1.534 2.887.555 4.228");
}

.m263k3bfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.495 14.81c-2.059-4.043-6.965-5.764-11.113-3.831a8.446 8.446 0 0 0-4.205 10.967zm20.328 7.106c1.778-4.175-.057-9.035-4.205-10.967s-9.054-.212-11.113 3.832zm-17.69-.361a2.9 2.9 0 0 0-.697.578c-1.071 1.221-.953 3.127.264 4.256");
}

.ufhkwtqlu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.559 30.96c-.2.217-.37.47-.5.755c-.674 1.478-.01 3.268 1.48 3.999");
}

.zs2qes99h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.611 26.32c.238.174.454.39.636.645c.943 1.322.635 3.206-.69 4.208m-8.418-2.263q-.437.09-.845.327c-1.405.817-1.9 2.66-1.106 4.118");
}

</style>
