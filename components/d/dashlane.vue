<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ypoxyib5o"/><path class="q80i31bdx"/><path class="g6um1oylm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dashlane" /></template>
<style>
.g6um1oylm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.06 29.63l-4.738-1.432A1.025 1.025 0 0 0 24 29.18v9.787c0 .452.296.85.729.981l4.738 1.431a1.025 1.025 0 0 0 1.321-.981V30.61c0-.452-.296-.851-.728-.982m6.788-13.883l-4.738-1.43a1.025 1.025 0 0 0-1.322.98V33.84c0 .452.296.85.73.981l4.737 1.431a1.025 1.025 0 0 0 1.322-.981V16.727c0-.452-.296-.851-.729-.982");
}

.q80i31bdx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.271 5.976l-4.738-1.432a1.025 1.025 0 0 0-1.321.982v9.787c0 .452.296.85.728.982l4.738 1.43a1.025 1.025 0 0 0 1.322-.98V6.956c0-.452-.296-.85-.729-.981m0 25.73l-4.738-1.43a1.025 1.025 0 0 0-1.321.98v9.788c0 .452.296.85.728.981l4.738 1.431A1.025 1.025 0 0 0 24 42.474v-9.787c0-.452-.296-.851-.729-.982M30.06 9.75l-4.738-1.43A1.025 1.025 0 0 0 24 9.3v9.788c0 .452.296.85.729.981l4.738 1.431a1.025 1.025 0 0 0 1.321-.981v-9.787c0-.452-.296-.851-.728-.982");
}

.ypoxyib5o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.483 5.976l-4.738-1.432a1.025 1.025 0 0 0-1.322.982v35.517c0 .452.296.85.729.981l4.738 1.431a1.025 1.025 0 0 0 1.322-.981V6.957c0-.452-.297-.85-.73-.981");
}

</style>
