<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="pzcs6vbpm"/><path class="r4bayqb_a"/><path class="rpns7lb4p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:circus-tent-sharp" /></template>
<style>
.pzcs6vbpm {
  d: path("m12.28 2.86l3.44 1.28l.28.11l-.28.11l-3.44 1.28l-.28.11v-3z");
}

.r4bayqb_a {
  d: path("M12 5.75c-2 3-4.75 4.75-8.75 5.75a2.19 2.19 0 0 0 4.38 0a2.19 2.19 0 0 0 4.37 0a2.19 2.19 0 0 0 4.38 0a2.19 2.19 0 0 0 4.37 0c-4-1-6.75-2.75-8.75-5.75ZM5.75 16.5h13.5v4.75H4.75V16.5z");
}

.rpns7lb4p {
  d: path("M9.25 21.25L12 18l2.75 3.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
