<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGeK3V9cAp)" class="zbm5yjb6p"/><path class="o72-dxbmi"/><defs><linearGradient id="SVGeK3V9cAp" x1="10.92" x2="17.923" y1="7.669" y2="19.374" gradientUnits="userSpaceOnUse"><stop class="hxaj89bom"/><stop offset=".52" class="q79ty0bgc"/><stop offset="1" class="wo_m12bse"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:azit" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hxaj89bom {
  stop-color: var(--svg-color--3938b8, #3938b8);
}

.o72-dxbmi {
  fill: var(--svg-color--5550d2, #5550d2);
  d: path("m13.435 16.909l7.565-12h-7.069l1.244 2.182h1.963l-7.592 12h11.078l-1.244-2.182z");
}

.q79ty0bgc {
  stop-color: var(--svg-color--3937bd, #3937bd);
}

.wo_m12bse {
  stop-color: var(--svg-color--5955d9, #5955d9);
}

.zbm5yjb6p {
  d: path("m11.874 5.166l-.141-.257L3 19.091h2.553l6.19-9.982l6.731 9.982H21z");
}

</style>
