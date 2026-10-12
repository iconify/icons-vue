<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="nu50zxb0n"/><path class="c6vi_0cog"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:catamaran-sharp" /></template>
<style>
.c6vi_0cog {
  d: path("M12 5.5v7H5.5l.63-.78l5.24-6.44l.63-.78zm0 7v3m-9.25 0h18.5m-17.5 0h3.5V20h-3.5v-1.75Zm13 0h3.5V20h-3.5v-1.75Z");
}

.nu50zxb0n {
  d: path("M12 3.75v8.75h7.5l-.61-.79l-6.28-8.17l-.61-.79z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
