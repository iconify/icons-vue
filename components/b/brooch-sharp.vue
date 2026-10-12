<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="iplt-mblh"/><circle class="gp0egaclj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:brooch-sharp" /></template>
<style>
.gp0egaclj {
  cx: 12px;
  cy: 12px;
  r: 3px;
}

.iplt-mblh {
  d: path("m12.82 3.82l.68.47l.82.58l1 .02l.82.01l1 .02l.33.95l.27.78l.33.94l.8.6l.65.5l.8.61l-.29.95l-.24.79l-.29.96l.29.96l.24.79l.29.95l-.8.61l-.65.5l-.8.6l-.33.94l-.27.78l-.33.95l-1 .02l-.82.01l-1 .02l-.82.58l-.68.47l-.82.57l-.82-.57l-.68-.47l-.82-.58l-1-.02l-.82-.01l-1-.02l-.33-.95l-.27-.78l-.33-.94l-.8-.6l-.65-.5l-.8-.61l.29-.95l.24-.79l.29-.96l-.29-.96l-.24-.79l-.29-.95l.8-.61l.65-.5l.8-.6l.33-.94l.27-.78l.33-.95l1-.02l.82-.01l1-.02l.82-.58l.68-.47l.82-.57z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
