<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="e8sr0bcyc"/><path class="zml1h0q7g"/><path class="eecfybbbd"/><path class="b22-7qb1v"/><path class="k3ti3vb9x"/><path class="uvs2-_xye"/><path class="tlh989bna"/><path class="zr35ecbmr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-sliders-line-duotone" /></template>
<style>
.b22-7qb1v {
  d: path("M11.4102 13.2188C11.4102 13.8918 10.8645 14.4375 10.1914 14.4375C9.51831 14.4375 8.97266 13.8918 8.97266 13.2188C8.97266 12.5457 9.51831 12 10.1914 12C10.8645 12 11.4102 12.5457 11.4102 13.2188Z");
}

.e8sr0bcyc {
  d: path("M13 2.2627V5.0003C13 7.35732 13 8.53583 13.7322 9.26806C14.4645 10.0003 15.643 10.0003 18 10.0003H21.58");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.eecfybbbd {
  d: path("M13.2441 13.2188L11.4102 13.2187");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k3ti3vb9x {
  d: path("M9.39062 17.2657L13.245 17.2656");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.tlh989bna {
  d: path("M6.95313 17.2656C6.95313 16.5925 7.49878 16.0469 8.17188 16.0469C8.84497 16.0469 9.39063 16.5925 9.39063 17.2656C9.39063 17.9387 8.84497 18.4844 8.17188 18.4844C7.49878 18.4844 6.95313 17.9387 6.95313 17.2656Z");
}

.uvs2-_xye {
  d: path("M5.11914 17.2656L6.95312 17.2656");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.zml1h0q7g {
  d: path("M8.97266 13.2186L5.1183 13.2187");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.zr35ecbmr {
  stroke-linejoin: round;
  d: path("M3.17139 3.17157C4.34296 2 6.23851 2 10.0296 2C11.5546 2 12.3173 2.00011 13.0093 2.26562C13.7012 2.53114 14.2651 3.03857 15.3929 4.05365L19.3516 7.61621C20.6558 8.78998 21.3078 9.3774 21.6538 10.1543C21.9998 10.9312 22 11.8079 22 13.5625V14C22 17.7712 22 19.6566 20.8284 20.8281C19.6569 21.9997 17.7712 22 14 22L9.9969 21.9997C6.22761 21.9997 4.34284 21.9997 3.17157 20.8284C2 19.6569 2 17.7712 2 14V9.9982C2 6.22817 2 4.34296 3.17139 3.17157Z");
}

</style>
