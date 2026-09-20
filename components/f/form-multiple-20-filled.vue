<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="ug-fufjpe"/><path class="dbc4j0rho"/><path class="zwn5_nbit"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:form-multiple-20-filled" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dbc4j0rho {
  d: path("M6 3h6a3 3 0 0 1 3 3v6a2.99 2.99 0 0 1-1.262 2.445A2.98 2.98 0 0 1 12 15H6a2.99 2.99 0 0 1-2.445-1.262A3 3 0 0 1 3 12V6a3 3 0 0 1 3-3m-.5 3a.5.5 0 0 0 0 1h7a.5.5 0 0 0 0-1zm1 6a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3m3-2a.5.5 0 0 0 0 1h3a.5.5 0 0 0 0-1z");
}

.ug-fufjpe {
  d: path("M6.5 11a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

.zwn5_nbit {
  d: path("M5.764 16c.55.614 1.348 1 2.236 1h4.5a4.5 4.5 0 0 0 4.5-4.5V8c0-.888-.386-1.687-1-2.236V12.5q0 .18-.018.358A3.5 3.5 0 0 1 12.5 16z");
}

</style>
