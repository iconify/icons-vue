<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="re_trpb5a"/><path class="jqh999btr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:condenser-mic-sharp" /></template>
<style>
.jqh999btr {
  d: path("M8.25 11H5.5v6.75h13V11h-2.75M12 17.75v3.5m-3 0h6");
}

.re_trpb5a {
  d: path("M8.25 2.75h7.5v12h-7.5zm0 4.25h7.5m-7.5 3.5h7.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
