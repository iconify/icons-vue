<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vl4p3_byc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:forest-sharp" /></template>
<style>
.vl4p3_byc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.18 8.05l2.38 3.04l.43.55h-1.26l.42.56l1.86 2.48l.42.56h-1.62l.44.55l2 2.5l.44.55H2.81l.44-.55l2-2.5l.44-.55H4.07l.42-.56l1.86-2.48l.42-.56H5.51l.43-.55l2.38-3.04l.43-.55zm3.22 2.25l.87-1.16h-1.26L15.25 5l3.24 4.14h-1.26l2.7 3.6h-1.62l2.88 3.6H14m-5.25 2.5v2.41m8-4.91v4.91m-14 0h18.5");
}

</style>
