<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="smbr-vnzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fancode" /></template>
<style>
.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.smbr-vnzh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m34.432 26.75l-.013.07c-.538 3.056-3.453 5.534-6.51 5.534h0c-3.056 0-5.097-2.478-4.558-5.535l.994-5.638c.54-3.057 3.454-5.535 6.51-5.535h0c3.057 0 5.098 2.478 4.559 5.535l-.012.068M13.973 24h5.43M12.5 32.354l2.946-16.708h8.353");
}

</style>
