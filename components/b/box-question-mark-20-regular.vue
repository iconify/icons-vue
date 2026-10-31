<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="tmqbukvsk"/><path class="ioi3okclk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:box-question-mark-20-regular" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ioi3okclk {
  d: path("M8.7 2.25a3.5 3.5 0 0 1 2.6 0l5.757 2.303c.57.228.943.78.943 1.393v4.31a5.5 5.5 0 0 0-1-.655V6.008l-6.5 2.6v2.118a5.5 5.5 0 0 0-1 1.482v-3.6L3 6.007v7.584c0 .204.125.388.314.464l5.757 2.303q.141.054.286.092q.22.577.557 1.084a3.5 3.5 0 0 1-1.214-.247l-5.757-2.304A1.5 1.5 0 0 1 2 13.592V5.946a1.5 1.5 0 0 1 .943-1.393zM3.847 5.27L10 7.73l2.53-1.012l-6.155-2.46zm7.082-2.092a2.5 2.5 0 0 0-1.858 0l-1.35.54l6.154 2.462l2.28-.91z");
}

.tmqbukvsk {
  d: path("M14.5 10a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9m0 6.38a.625.625 0 1 0 0 1.25a.625.625 0 0 0 0-1.25m0-4.876c-1.048 0-1.864.817-1.854 1.954a.5.5 0 1 0 1-.01c-.005-.579.36-.944.854-.944c.472 0 .853.391.854.949c0 .202-.072.315-.36.544l-.278.215c-.506.404-.716.718-.716 1.289a.5.5 0 0 0 .992.09l.01-.157c.018-.147.101-.253.347-.448l.277-.215c.513-.41.728-.732.728-1.318c0-1.104-.823-1.95-1.854-1.95");
}

</style>
