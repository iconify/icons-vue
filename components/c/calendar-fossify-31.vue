<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="xi707eb2c"/><path class="ly80cbccv"/></g><path class="gdpz_rbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-fossify-31" /></template>
<style>
.gdpz_rbbn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.532 9.567h24.936a4 4 0 0 1 4 4V38.5a4 4 0 0 1-4 4H11.532a4 4 0 0 1-4-4V13.567a4 4 0 0 1 4-4M13.715 5.5v4.068M34.14 5.5v4.068M9.731 19.89h28.36");
}

.ly80cbccv {
  d: path("M16.165 26.64c.775-.646 1.61-.94 3.485-.936l.436.003a2.8 2.8 0 0 1 2.8 2.799v0a2.8 2.8 0 0 1-2.8 2.8m-2.152-.001h2.152m6.949-4.151l2.8-1.54m0 0v11.2");
}

.xi707eb2c {
  d: path("M16.166 35.96c.774.647 1.608.944 3.483.944h.437a2.8 2.8 0 0 0 2.8-2.8v0a2.8 2.8 0 0 0-2.8-2.799");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
