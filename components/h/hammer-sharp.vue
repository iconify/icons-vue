<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ojyix-7hv"/><path class="mw_6s4rei"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hammer-sharp" /></template>
<style>
.mw_6s4rei {
  d: path("m12.3 10.85l.25.26l1.06 1.06l-1.06 1.06l-6.36 6.37l-1.06 1.06l-1.06-1.06l-.26-.26l-1.06-1.06l1.06-1.06l6.37-6.37l1.06-1.06z");
}

.ojyix-7hv {
  d: path("m11.12 3.5l.23.02l1.24.16l.88.88l6.9 6.9l.88.88l-.88.88l-1.97 1.97l-.88.88l-.88-.88l-6.9-6.89l-.88-.88l-.16-1.24l-.02-.24l-.16-1.24l.68-.68l.68-.68z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
