<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="qmlvdtf2m"/><path class="gyqer07rf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:balloon-star-sharp" /></template>
<style>
.gyqer07rf {
  d: path("M12 13.6c1 2.25-1 4.5 0 7.65");
}

.qmlvdtf2m {
  d: path("m12.38 3.32l1.36 2.95l.38.82l.89.1l3.23.39l.89.1l-.66.61l-2.39 2.21l-.66.61l.18.89l.63 3.18l.18.89l-.79-.44l-2.83-1.59l-.79-.44l-.79.44l-2.83 1.59l-.79.44l.18-.89L8.4 12l.18-.89l-.66-.61l-2.39-2.21l-.66-.61l.89-.1l3.23-.39l.89-.1l.38-.82l1.36-2.95l.38-.82z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
