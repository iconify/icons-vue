<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="aqhok2bbj"/><path class="wtr0t5bay"/><path class="xo0gn7bpl"/><path class="zkjcpqlzm"/><path class="sm0uzcbjt"/><path class="jed98nbpx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:help-broken" /></template>
<style>
.aqhok2bbj {
  cx: 12px;
  cy: 12px;
  r: 4px;
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jed98nbpx {
  d: path("M9.41235 2.33892C11.0533 1.89775 12.8289 1.86936 14.5882 2.34078C19.9229 3.7702 23.0887 9.25357 21.6593 14.5882C20.2299 19.9229 14.7465 23.0887 9.41185 21.6593C4.07719 20.2299 0.911364 14.7465 2.34078 9.41185C2.8122 7.65248 3.72457 6.12901 4.92711 4.92847");
}

.sm0uzcbjt {
  d: path("M19.0723 19.072L14.8284 14.8284");
}

.wtr0t5bay {
  d: path("M14.8286 9.17129L19.0727 4.92749");
}

.xo0gn7bpl {
  d: path("M4.92773 19.0723L9.17155 14.8286");
}

.zkjcpqlzm {
  d: path("M9.17133 9.17157L4.92827 4.92822");
}

</style>
