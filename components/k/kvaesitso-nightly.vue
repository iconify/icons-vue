<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="iv34yub_k"/><path class="u961brnit"/><path class="fb-txnbqk"/><path class="yred2ccsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kvaesitso-nightly" /></template>
<style>
.fb-txnbqk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.926 19.778v7.807c0 .958.777 1.734 1.735 1.734h24.287c.958 0 1.734-.776 1.734-1.734v-7.807c0-.958-.776-1.735-1.735-1.735H11.661c-.958 0-1.735.777-1.735 1.735M34.639 32.66a2 2 0 0 0-1.14-.357H14.11a2 2 0 0 0-2 2v7.61");
}

.iv34yub_k {
  cx: 38.5px;
  cy: 38.499px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.u961brnit {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.85 42.499v-8l5.3 8v-8M28.983 20.862h5.638V26.5h-5.638zm-7.936 0h5.638V26.5h-5.638zm-7.937 0h5.638V26.5H13.11zm-4.474-5.103l13.46-6.715a4.15 4.15 0 0 1 3.66-.023L39.365 15.6");
}

.yred2ccsw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.432 43.326A21.4 21.4 0 0 1 24 45.5C12.126 45.5 2.5 35.874 2.5 24S12.126 2.5 24 2.5S45.5 12.126 45.5 24c0 3.383-.781 6.583-2.173 9.43");
}

</style>
