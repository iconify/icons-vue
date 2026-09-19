<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="e6v949l6y"/><path class="jabqw0b9z"/><path class="w-00_1myl"/><circle class="kcttthfgs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ippb-mobile" /></template>
<style>
.e6v949l6y {
  d: path("M4.5 31.497s4.981-4.515 11.04-.494c0 0 5.075 3.027 9.497-.818c2.901-2.523 6.181-6.185 9.674-10.325c1.793-2.125 5.201-6.515 8.789-6.811");
}

.jabqw0b9z {
  d: path("M8.33 26.794c1.864-.458 4.155-.644 6.702 1.046c0 0 5.03 3.173 9.606-.488c0 0 1.482-.636 9.674-10.443c0 0 2.328-2.916 4.944-4.935");
}

.kcttthfgs {
  cx: 24.075px;
  cy: 26.738px;
  r: 9.288px;
}

.w-00_1myl {
  d: path("M12.07 23.877c.95.08 1.935.538 2.836 1.136c0 0 4.755 3.282 9.332-.378c0 0 1.832-1.278 9.529-10.37c0 0 .394-.495 1.04-1.216");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
