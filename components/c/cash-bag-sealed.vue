<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ir__4fq4f"/><path class="npoct7a1d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cash-bag-sealed" /></template>
<style>
.ir__4fq4f {
  d: path("M19.629 12.004C18.796 9.989 17.317 8.159 15 7H9c-4 2-5.5 6-5.5 9.5c0 3 2 5 5 5h3.245M9 7L7.5 3h9L15 7");
}

.npoct7a1d {
  d: path("M12.75 12c-.25-.75-1-1.25-2.25-1.25s-2 .75-2 1.75c0 1.466 2.282 1.454 3.502 2.229m-.307 2.764a2.8 2.8 0 0 1-1.195.257c-1.25 0-2-.5-2.25-1.25m2.25-7v1.25m0 7V19m4-1.5h7V22h-7Zm1.75 0v-1.25a1.75 1.75 0 0 1 3.5 0v1.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
