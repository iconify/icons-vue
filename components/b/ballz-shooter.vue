<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="fgqjxw7_l"/><path class="x5_0jqb4d"/><path class="j8-rqqbmt"/><path class="r1fcp8b9h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ballz-shooter" /></template>
<style>
.fgqjxw7_l {
  cx: 27.317px;
  cy: 20.082px;
  r: 3.794px;
}

.j8-rqqbmt {
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.r1fcp8b9h {
  d: path("M5.618 11.656h7.992V5.5m20.78 0v6.156h7.895M15.973 5.5v6.156h16.054V5.5");
}

.x5_0jqb4d {
  d: path("m21.9 28.866l2.618-4.21m.374 4.96l2.645-4.254m-7.673 1.251l2.558-4.115M5.628 31.223c9.18.346 17.348 4.65 22.846 11.256M16.863 27.55l8.916 5.148l-1.469 2.587a32 32 0 0 0-9.003-5.018z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
