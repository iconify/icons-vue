<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="tpw9ai2qg"/><circle class="ky9ghfh4c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:amethyst" /></template>
<style>
.ky9ghfh4c {
  cx: 26.819px;
  cy: 17.312px;
  r: 1.134px;
}

.tpw9ai2qg {
  d: path("M24 3.5L5.768 16.392c.046 5.072.021 10.144 0 15.216l3.687 2.608c.718-15.085 7.231-21.088 7.231-21.088s.198.607 2.385.858c2.188.25 9.393-1.17 11.419 1.095s-.382 4.21 1.308 5.895s6.253 2.196 5.748 3.74s-3.782.645-7.836.636c-4.054-.008-3.43 1.352-6.61 1.27c-4.824 3.416-.468 11.369-3.412 14.817l-.012.004L24 44.5l18.23-12.892c-.045-5.072-.02-10.144 0-15.216z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
