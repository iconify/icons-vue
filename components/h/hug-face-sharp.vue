<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="k8gzv6bze"/><path class="ajmmxq1oo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hug-face-sharp" /></template>
<style>
.ajmmxq1oo {
  d: path("m8.5 9l1.125-1.432L10.75 9m2.5 0l1.125-1.432L15.5 9m-5.75 3.75l.975.9h2.55l.975-.9M2.75 15.5A10.5 10.5 0 0 0 7.56 20m13.69-4.5a10.5 10.5 0 0 1-4.81 4.5");
}

.k8gzv6bze {
  cx: 12px;
  cy: 10.5px;
  r: 7px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
