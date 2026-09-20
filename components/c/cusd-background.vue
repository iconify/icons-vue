<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="bfxymhymw"/><path class="hg6eyacwa"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cusd-background" /></template>
<style>
.bfxymhymw {
  fill: var(--svg-color--45cd85, #45cd85);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.hg6eyacwa {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.775 5.025c.56.05 1.14.15 1.725.31v1.59c-.3-.22-1.04-.665-2.415-.665s-1.615.59-1.565.89c-.04.135.1.465.95.7c.185.05.41.09.67.14c1.305.235 3.36.615 3.36 2.6c0 1.375-1.155 2.205-2.725 2.375L15.95 14H14.4l.165-1.03A7.6 7.6 0 0 1 12 12.25v-1.66c.71.45 4.725 1.865 4.935 0c.065-.61-.775-.79-1.78-1.01C13.74 9.28 12 8.9 12 7.155c0-1.31 1.08-1.985 2.56-2.125L14.4 4h1.555l-.175 1.025zM12 18.5a5 5 0 0 0 4.585-3h1.6a6.497 6.497 0 0 1-7.947 4.257A6.501 6.501 0 0 1 10 7.315v1.6a5 5 0 0 0 2 9.586");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
