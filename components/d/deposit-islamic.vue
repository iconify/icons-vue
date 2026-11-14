<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h6tldxehp"/><path class="f25xatb4q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:deposit-islamic" /></template>
<style>
.f25xatb4q {
  d: path("M14 9.75c-.25-.5-1-1-2-1c-1.25 0-2 .75-2 1.5c0 1.615 3.405 1.101 3.932 2.976m-1.603 1.998a2 2 0 0 1-.329.026c-1 0-1.75-.5-2-1m2-6.75v1.25m0 6.5v.6m7.5-.6a3.25 3.25 0 1 0 0 5.5a3 3 0 0 1 0-5.5Z");
}

.h6tldxehp {
  d: path("M11 3.5a8.5 8.5 0 0 0 0 17Zm2 10.826V3.5q.209 0 .417.01t.416.031t.414.051q.206.031.411.072q.204.041.407.091q.202.051.402.112q.199.06.396.131q.196.07.389.15t.381.169t.373.188t.363.205q.179.108.352.224q.173.115.341.24q.167.124.329.256q.161.133.315.273q.155.14.303.288q.147.147.287.302q.14.154.272.316q.133.161.257.329q.124.167.24.341q.116.173.223.352q.108.179.206.363t.187.373t.169.381t.15.389t.131.396t.111.402t.092.407t.071.411t.051.414t.031.416t.01.417q0 .601-.084 1.195");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
