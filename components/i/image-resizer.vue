<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="djss33kfj"/><path class="bgwy2obhl"/><circle class="lk-j1dbrk"/><path class="wadju6boh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:image-resizer" /></template>
<style>
.bgwy2obhl {
  d: path("M42.457 3.492h-8.45c-.55 0-1 .45-1 1v8.45c0 .55.45 1 1 1h8.45c.55 0 1-.45 1-1v-8.45c0-.55-.45-1-1-1M5.515 35.52s4.037-2.855 6.236-3.966c1.535-.775 3.098-1.996 4.812-1.86c1.85.146 3.05 2.216 4.813 2.8c.831.275 1.743.416 2.611.295c1.037-.143 2.02-.633 2.907-1.188c2.228-1.396 3.66-3.847 5.874-5.266c.791-.506 1.648-1.075 2.586-1.12c2.413-.113 4.519 1.987 6.892 2.24");
}

.djss33kfj {
  d: path("M32.79 5.5H9.5a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4V14.063");
}

.lk-j1dbrk {
  cx: 13.98px;
  cy: 13.253px;
  r: 3.966px;
}

.wadju6boh {
  d: path("m36.412 8.21l1.818-1.818v4.66m1.822-2.853L38.234 6.38v4.66");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
