<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ztqm_7bzq"/><path class="n_49ddckd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:courthouse-sharp" /></template>
<style>
.n_49ddckd {
  d: path("M12 10v8m-2.25 0h4.5M7.5 11.25h9m-9 0l-1 3.25l1 2.182l1-2.182Zm9 0l-1 3.25l1 2.182l1-2.182Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ztqm_7bzq {
  d: path("M3.25 20.25v-12l.86-.51l7.03-4.23L12 3l.86.51l7.03 4.23l.86.51v13H3.25z");
}

</style>
