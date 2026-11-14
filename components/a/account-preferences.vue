<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z5hv4nb3d"/><path class="s2vf03byp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:account-preferences" /></template>
<style>
.s2vf03byp {
  d: path("M13.75 15.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm3.5 0H22m-3.75 4.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm-4.75 0h4.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z5hv4nb3d {
  d: path("M10.994 17.496C10.73 17.348 2.5 12.67 2.5 7.75C2.5 5.4 4.4 3.5 6.75 3.5C8.5 3.5 10.1 4.5 11 6c.9-1.5 2.5-2.5 4.25-2.5c2.35 0 4.25 1.9 4.25 4.25c0 1.419-.684 2.817-1.665 4.093m-6.613 5.529q-.18.105-.215.124");
}

</style>
