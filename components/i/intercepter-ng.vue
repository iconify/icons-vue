<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="u4-jfui_w"/><path class="iymnf2nrv"/><path class="aovi1ofkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:intercepter-ng" /></template>
<style>
.aovi1ofkm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.32 24a9 9 0 0 0-.355-2.484l4.294-2.861l-2.094-3.807l-5.723 1.406a15.2 15.2 0 0 0-3.205-2.102l.869-5.142l-4.76-1.46l-3.677 4.73c-.303-.013-.603-.035-.91-.035s-.607.022-.91.035l-3.678-4.73l-4.76 1.46l.869 5.142a15.2 15.2 0 0 0-3.205 2.102l-5.722-1.406l-2.094 3.807l4.294 2.86a8.86 8.86 0 0 0 0 4.97l-4.294 2.86l2.094 3.807l5.722-1.406a15.2 15.2 0 0 0 3.205 2.102l-.868 5.142l4.759 1.46l3.678-4.73c.302.013.602.034.91.034s.607-.021.91-.034l3.678 4.73l4.759-1.46l-.868-5.142a15.2 15.2 0 0 0 3.205-2.102l5.722 1.406l2.094-3.807l-4.294-2.86A9 9 0 0 0 41.32 24");
}

.iymnf2nrv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.18 24a15.818 15.818 0 0 0 27.158 0m0 0a15.818 15.818 0 0 0-27.159 0");
}

.u4-jfui_w {
  cx: 25.759px;
  cy: 24px;
  r: 7.706px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
