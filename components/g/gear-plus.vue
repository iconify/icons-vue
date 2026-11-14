<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rj-kgvs0b"/><path class="yl72mu_gb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gear-plus" /></template>
<style>
.rj-kgvs0b {
  d: path("m8.25 4.606l.135-1.798h1.73l.135 1.798l1.577.654l1.366-1.177l1.224 1.224l-1.177 1.366l.654 1.577l1.798.135v1.73l-1.798.135l-.654 1.577l1.177 1.366l-1.224 1.224l-1.366-1.177l-1.577.654l-.135 1.798h-1.73l-.135-1.798l-1.577-.654l-1.366 1.177l-1.224-1.224l1.177-1.366l-.654-1.577l-1.798-.135v-1.73l1.798-.135l.654-1.577l-1.177-1.366l1.224-1.224L6.673 5.26Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yl72mu_gb {
  d: path("M7.5 9.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM18 15v6m-3-3h6");
}

</style>
