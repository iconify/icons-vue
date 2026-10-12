<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="dbgvcxwad"/><path class="p6wwfac-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dizzy-sharp" /></template>
<style>
.dbgvcxwad {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

.p6wwfac-s {
  d: path("m9.4 10l.19-.415l-.22-.455l-.258-.516L8.5 8.45l-.686-.184l-.644.404l-.704.452L6.3 10l-.181.956l.591.834l.663.895l1.127.165M14.6 10l-.19-.415l.22-.455l.258-.516l.612-.164l.686-.184l.644.404l.704.452l.166.878l.181.956l-.591.834l-.663.895l-1.127.165m-6.25 3.9l.915-1.281l.915 1.281l.915 1.281l.915-1.281l.915-1.281l.915 1.281");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
