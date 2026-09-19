<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hb_l6zfnx"/><rect class="pvua4hbxe"/><path class="aa16owblt"/><circle class="lelvoupum"/><path class="p35vusn2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:box-box-club" /></template>
<style>
.aa16owblt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.005 36.123v4.585h2.487m-4.196-1.538v.018c0 .84-.738 1.52-1.648 1.52S25 40.027 25 39.187V37.64c0-.839.738-1.519 1.648-1.519s1.648.68 1.648 1.519v.019m5.904-1.536v3.066c0 .839.738 1.519 1.648 1.519s1.648-.68 1.648-1.52v-3.065m3.76 2.292c.687 0 1.244.513 1.244 1.146s-.557 1.146-1.244 1.146h-2.052v-4.585h2.052c.687 0 1.244.513 1.244 1.146s-.557 1.147-1.244 1.147m0 0h-2.05M7.926 25a1.5 1.5 0 0 0-1.342 2.172l3.29 6.578l-3.29 6.578A1.5 1.5 0 0 0 7.926 42.5h12.648a1.5 1.5 0 0 0 1.342-2.172l-3.29-6.578l3.29-6.578A1.5 1.5 0 0 0 20.574 25zM23 9.875C23 7.479 21.021 5.5 18.625 5.5H7A1.5 1.5 0 0 0 5.5 7v14.5A1.5 1.5 0 0 0 7 23h11.625C21.021 23 23 21.021 23 18.625c0-2.389-1.967-4.359-4.353-4.375C21.033 14.234 23 12.264 23 9.875");
}

.hb_l6zfnx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.694 26.496L42.5 33.75m0-7.254l-4.806 7.254m-9.702-3.627a1.813 1.813 0 1 1 0 3.627H25v-7.254h2.992a1.813 1.813 0 1 1 0 3.627m0 0h-2.988");
}

.lelvoupum {
  cx: 33.75px;
  cy: 14.25px;
  r: 8.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.p35vusn2n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.375 9.875l8.75 8.75");
}

.pvua4hbxe {
  width: 4.806px;
  height: 7.254px;
  x: 31.347px;
  y: 26.496px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.403px;
  ry: 2.403px;
}

</style>
