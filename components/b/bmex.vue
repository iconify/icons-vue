<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGhbH6qdVD)" class="l1lyo562o"/><path fill="url(#SVG2kZGedeC)" class="a3qg1ccej"/><defs><linearGradient id="SVGhbH6qdVD" x1="15.003" x2="15.003" y1="4.688" y2="19.313" gradientUnits="userSpaceOnUse"><stop class="vqi-c0hjz"/><stop offset="1" class="cnqpokr8f"/></linearGradient><linearGradient id="SVG2kZGedeC" x1="15.656" x2="15.656" y1="4.688" y2="19.313" gradientUnits="userSpaceOnUse"><stop class="uj4il9fmi"/><stop offset="1" class="c95i7cwvq"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bmex" /></template>
<style>
.a3qg1ccej {
  d: path("M17.44 19.313L21 4.688h-3.375l-2.25 9H12l-1.687 5.624z");
}

.c95i7cwvq {
  stop-color: var(--svg-color--2253d3, #2253d3);
}

.cnqpokr8f {
  stop-color: var(--svg-color--b42600, #b42600);
}

.ft5dv1b6b {
  fill: none;
}

.l1lyo562o {
  d: path("M6.937 4.688L3 19.313h3.375l2.25-9h3.64l1.422-5.625z");
}

.uj4il9fmi {
  stop-color: var(--svg-color--2560e2, #2560e2);
}

.vqi-c0hjz {
  stop-color: var(--svg-color--fb2f03, #fb2f03);
}

</style>
