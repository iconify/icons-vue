<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uzjo1db4j"/><path class="z-p8kctxg"/><path class="k1sd-jbal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:listen-audiobook-player" /></template>
<style>
.k1sd-jbal {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m14.397 8.065l19.205-.007c.554 0 1.081.112 1.56.314M14.397 6.307L33.602 6.3c.554 0 1.081.112 1.56.314");
}

.uzjo1db4j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m32.541 26.52l-12.01 6.935v-13.87zM10.396 7.193c0 1.267 1.785 2.694 4.002 2.687");
}

.z-p8kctxg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.398 43.5h19.204a3.993 3.993 0 0 0 4.002-3.984V8.502A3.993 3.993 0 0 0 33.62 4.5H14.398c-2.217 0-4.002 1.427-4.002 2.693v32.305A3.993 3.993 0 0 0 14.38 43.5zV9.88l19.204-.006a3.993 3.993 0 0 1 4.002 3.984v.017");
}

</style>
