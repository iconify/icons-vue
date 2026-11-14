<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ibdmb-bqs"/><path class="e278u0eju"/><path class="a6yqt2buc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hoa-rules" /></template>
<style>
.a6yqt2buc {
  d: path("M11.5 14v-2.5h2V14");
}

.e278u0eju {
  d: path("M9 4.75h7V14H9Zm2 2.75h.01m2.99 0h.01");
}

.ibdmb-bqs {
  d: path("M4.5 19.25V5A2.5 2.5 0 0 1 7 2.5h12.5V17H6.75a2.25 2.25 0 0 0 0 4.5H19.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
