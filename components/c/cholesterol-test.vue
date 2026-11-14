<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x4a6mcbdq"/><path class="t_p7fpbuz"/><path class="k_he6cb8q"/><path class="pbeiyabda"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cholesterol-test" /></template>
<style>
.k_he6cb8q {
  d: path("M16.25 14.25v5.25c0 2.25 3.5 2.25 3.5 0v-5.25m-4.5 0h5.5");
}

.pbeiyabda {
  fill: currentColor;
  d: path("M16.25 17.5h3.5v2c0 2.25-3.5 2.25-3.5 0Z");
}

.t_p7fpbuz {
  fill: currentColor;
  d: path("M6.75 12a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm3.5 0a1 1 0 1 0 2 0a1 1 0 1 0-2 0ZM8.5 15.25a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x4a6mcbdq {
  d: path("M13.465 17.209c-1.067.953-2.462 1.541-3.965 1.541c-3.25 0-6-2.75-6-6c0-3.5 3-6.5 6-10.25c2.63 3.288 5.26 5.999 5.869 8.976");
}

</style>
