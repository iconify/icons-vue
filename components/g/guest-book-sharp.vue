<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="f_gfc_bjd"/><path class="lz0uckojb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:guest-book-sharp" /></template>
<style>
.f_gfc_bjd {
  d: path("m15.53 6.22l.34-.94l.13-.38l.35-.19l3.4-1.87l.35-.19l.23.33l.54.79l.23.33l-.35.2l-3.3 1.9l-.35.2l-.4.05l-.9.1l-.4.05zM12 10.75c-2.25-1.5-5.75-2-9.25-1.25v10.75c3.25-.75 6.5-.25 9.25 1c2.75-1.25 6-1.75 9.25-1V9.5c-3.5-.75-7-.25-9.25 1.25Z");
}

.lz0uckojb {
  d: path("M12 10.75v10.5M4.5 13l2.722-.389L9.5 13.75m-5 2.5l2.722-.389L9.5 17m5-.75c.75-1.5 1.5-1.5 1.5 0s.75 1.5 1.5 0l.775-1.55l.975 1.3");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
