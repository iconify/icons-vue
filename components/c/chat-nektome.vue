<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jk3webb2h"/><path class="rkboebcqp"/><circle class="wlntmkyli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:chat-nektome" /></template>
<style>
.jk3webb2h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.916 34.645c-2.179 1.929-4.701 2.84-8.248 3.172c2.84-1.683 4.658-3.168 5.486-6.302C11.274 31.167 4.5 26.178 4.5 20.372c0-5.811 6.479-11.642 14.384-12.059l1.193 1.382c5.953 0 11.099 2.509 13.538 6.15");
}

.rkboebcqp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.9 21.638c-5.3 0-9.596 3.288-9.596 7.344s4.297 7.343 9.597 7.344l.166-.008c.702 1.615 2.919 3.47 6.322 3.365c-1.799-.948-2.616-2.126-2.79-3.925c3.574-1.141 5.9-3.814 5.901-6.776c0-4.056-4.297-7.344-9.598-7.344zm-18.15-4.079c0-.972.33-1.945.987-2.593c.658-.648 1.48-.972 2.632-.972c1.973 0 3.617 1.62 3.617 3.565s-.292 1.984-.986 2.593c-.788.69-2.631 1.62-2.631 3.079");
}

.wlntmkyli {
  cx: 19.369px;
  cy: 27.12px;
  r: 0.75px;
  fill: currentColor;
}

</style>
