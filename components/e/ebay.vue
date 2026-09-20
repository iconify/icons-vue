<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="i-_3-n3vt"/><path class="t4oujbbcw"/></g><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ebay" /></template>
<style>
.i-_3-n3vt {
  d: path("M38.5 24.81v3.357a2.48 2.48 0 0 1-2.478 2.479h-.02a2.45 2.45 0 0 1-1.76-.73");
}

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

.t4oujbbcw {
  d: path("M38.5 20.702v4.107a2.49 2.49 0 0 1-2.488 2.489h-.01a2.49 2.49 0 0 1-2.479-2.489v-4.107m-19.356 5.297a2.5 2.5 0 0 1-2.149 1.299a2.49 2.49 0 0 1-2.498-2.479V23.19a2.49 2.49 0 0 1 2.488-2.488h.01a2.49 2.49 0 0 1 2.479 2.488V24H9.5m20.996.81a2.49 2.49 0 0 1-2.489 2.488a2.49 2.49 0 0 1-2.478-2.489V23.19a2.49 2.49 0 0 1 2.478-2.488a2.49 2.49 0 0 1 2.488 2.488m0 4.108v-6.596m-12.97 2.488a2.49 2.49 0 0 1 2.488-2.488a2.49 2.49 0 0 1 2.478 2.488v1.62a2.49 2.49 0 0 1-2.478 2.488a2.49 2.49 0 0 1-2.489-2.489m0 2.489v-9.943");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
