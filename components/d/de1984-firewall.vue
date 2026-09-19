<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kg4ghsblu"/><g class="y9tr6bcfx"><path class="sdlrp7soj"/><circle class="txhjl0bmh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:de1984-firewall" /></template>
<style>
.kg4ghsblu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 43.5c9.043-3.117 15.489-10.363 16.5-19.589c.28-4.005.257-8.025-.071-12.027a2.54 2.54 0 0 0-2.468-2.366c-4.091-.126-8.846-.808-12.52-4.427a2.05 2.05 0 0 0-2.881 0c-3.675 3.619-8.43 4.301-12.52 4.427a2.54 2.54 0 0 0-2.468 2.366A79.4 79.4 0 0 0 7.5 23.911C8.512 33.137 14.957 40.383 24 43.5");
}

.sdlrp7soj {
  d: path("M24 15.326c-4.339 0-8.102 2.445-10 6.03c1.898 3.585 5.661 6.03 10 6.03s8.102-2.445 10-6.03c-1.898-3.585-5.661-6.03-10-6.03");
}

.txhjl0bmh {
  cx: 24px;
  cy: 21.356px;
  r: 3.615px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
