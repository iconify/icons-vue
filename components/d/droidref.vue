<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="jlyultbfy"/><path class="v34dnbb7r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:droidref" /></template>
<style>
.jlyultbfy {
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

.v34dnbb7r {
  d: path("M26.275 31.472V16.528h5.071c2.867 0 5.19 2.247 5.19 5.019s-2.323 5.019-5.19 5.019h-5.071m5.071 0l5.07 4.902m-24.953.004V16.528h3.485c3.743 0 6.777 2.927 6.777 6.538v1.868c0 3.61-3.034 6.538-6.777 6.538z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
