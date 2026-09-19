<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="ysv3nlbpu"/><path class="y6l-y4vnh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ea-sports-fc-companion" /></template>
<style>
.y6l-y4vnh {
  d: path("m32.418 27.365l-2.064 3.456h0h-7.495c-.518 0-.725-.36-.464-.808l7.02-12.026c.26-.448.888-.808 1.406-.808H38.5l-2.063 3.454m-10.349-3.454H18.41c-.519 0-1.146.36-1.407.808L9.5 30.82");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ysv3nlbpu {
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4m3.752 18.903h8.454");
}

</style>
