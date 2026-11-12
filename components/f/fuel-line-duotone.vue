<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="yxd5kybqw"/><path class="j2ad96byc"/><path class="jhiwn9g1n"/><path class="uacjgs3aj"/><path class="ew__bm7mg"/><path class="kra2wmb9i"/><path class="c5hy1iqkr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:fuel-line-duotone" /></template>
<style>
.c5hy1iqkr {
  d: path("M10.9442 5.23713C10.7929 4.66113 10.3519 4.21122 9.78716 4.05687C9.57907 4 9.32544 4 8.81818 4H8C6.7206 4 6.08089 4 5.64021 4.34492C5.52676 4.43372 5.4252 4.53731 5.33815 4.65303C5 5.10254 5 5.75506 5 7.06009");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ew__bm7mg {
  d: path("M15 17L16 18");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j2ad96byc {
  d: path("M12 17C10.5858 17 9.87868 17 9.43934 16.5607C9 16.1213 9 15.4142 9 14C9 12.5858 9 11.8787 9.43934 11.4393C9.87868 11 10.5858 11 12 11C13.4142 11 14.1213 11 14.5607 11.4393C15 11.8787 15 12.5858 15 14C15 15.4142 15 16.1213 14.5607 16.5607C14.1213 17 13.4142 17 12 17Z");
}

.jhiwn9g1n {
  d: path("M15 11L16 10");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.kra2wmb9i {
  d: path("M9 17L8 18");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.uacjgs3aj {
  d: path("M9 11L8 10");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.yxd5kybqw {
  d: path("M8 22H16C18.8284 22 20.2426 22 21.1213 21.1042C22 20.2085 22 18.7668 22 15.8834V10.2325C22 6.30539 22 4.34183 20.7359 3.42756C19.4718 2.51329 17.6539 3.16195 14.0179 4.45927L6.0179 7.3137C4.07697 8.00623 3.1065 8.3525 2.55325 9.14745C2 9.94241 2 10.9906 2 13.0869V15.8834C2 18.7668 2 20.2085 2.87868 21.1042C3.75736 22 5.17157 22 8 22Z");
}

</style>
