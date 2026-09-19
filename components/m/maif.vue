<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="h01tyzbfu"><path class="ypphz-b-u"/><path class="ll3i0366u"/><path class="lrj0jmblu"/><path class="la4a_3bqz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:maif" /></template>
<style>
.h01tyzbfu {
  fill: none;
  stroke: currentColor;
}

.la4a_3bqz {
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.787 30.618L26.945 24l2.157 6.638");
}

.ll3i0366u {
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.392 30.631V24l3.319 6.638l3.319-6.628v6.628m12.586-3.319h2.158m-2.158 3.319V24h3.319");
}

.lrj0jmblu {
  d: path("M28.38 28.418h-2.876");
}

.ypphz-b-u {
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.371 8.714L4.5 33.806l39 5.48zM31.859 24v6.638");
}

</style>
