<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="k7mze5beq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:audiorelay" /></template>
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

.k7mze5beq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.35 12.548l-.316 13.282l-2.949 2.948c-.78.78-.78 2.046 0 2.826l7.088 7.087c.78.781 2.046.781 2.826 0l2.948-2.948l13.282-.316c2.868 0 2.844-1.802.91-3.736L17.086 11.639c-1.352-1.353-3.682-1.331-3.735.91zM37.73 22.55l-.001-.032c-.143-4.518-3.084-8.817-7.275-10.539c-1.348-.59-2.79-.9-4.24-.947m7.529 11.669c-.118-3.3-2.458-6.439-5.675-7.342a7.5 7.5 0 0 0-2.005-.337");
}

</style>
