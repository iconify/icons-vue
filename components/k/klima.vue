<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="kk3zybgtm"><path clip-rule="evenodd" class="zo-x662ph"/><path class="x5hw77bor"/><path class="nhm13fs8h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:klima" /></template>
<style>
.kk3zybgtm {
  fill: var(--svg-color--00cd34, #00cd34);
}

.nhm13fs8h {
  d: path("M4.125 11.438h15.75v1.124H4.125z");
}

.x5hw77bor {
  d: path("m11.995 6.938l8.988 13.5h-5.045v-1.125h2.88L12 9.188L5.183 19.313h2.88v1.125H3z");
}

.zo-x662ph {
  fill-rule: evenodd;
  d: path("m21 3.563l-8.995 13.5l-8.988-13.5zm-2.183 1.125L12 14.813L5.182 4.688z");
}

</style>
