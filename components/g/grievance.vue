<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kghai3b_c"/><path class="j-tkk1buy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:grievance" /></template>
<style>
.j-tkk1buy {
  d: path("m5.5 17l-2 4.5L9 18.75M12 7.5v3.75m0 3h.01");
}

.kghai3b_c {
  d: path("m12 1.75l2.24 2.355l3.197-.588l.428 3.222l2.932 1.403L19.25 11l1.547 2.858l-2.932 1.403l-.428 3.222l-3.197-.588L12 20.25l-2.24-2.355l-3.197.588l-.428-3.222l-2.932-1.403L4.75 11L3.203 8.142l2.932-1.403l.428-3.222l3.197.588Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
