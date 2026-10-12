<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="xan4yvbaa"/><path class="ooj2vrroy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ev-charger-sharp" /></template>
<style>
.ooj2vrroy {
  d: path("m10.5 5l-3 4.25h3.75l-3 4.25m.5 2.25v3h6.5m0-2h4v4h-4zm4 1.25h2m-2 1.5h2");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xan4yvbaa {
  d: path("M3.25 2.75h11v13h-11z");
}

</style>
