<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="kloex7bzq"/><path class="xb_kw9mli"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cease-desist-sharp" /></template>
<style>
.kloex7bzq {
  d: path("M4.75 2.75h14.5v18.5H4.75zm3.5 3.5h7.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xb_kw9mli {
  d: path("m15.28 15.95l-1.33 1.33l-.42.42h-3.06l-.42-.42l-1.33-1.33l-.42-.42v-3.06l.42-.42l1.33-1.33l.42-.42h3.06l.42.42l1.33 1.33l.42.42v3.06zM10.25 14h3.5");
}

</style>
