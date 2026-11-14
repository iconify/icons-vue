<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cgr3wrb9f"/><path class="jv4-5y5ol"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gift-card-redeem" /></template>
<style>
.cgr3wrb9f {
  d: path("M12.8 16H2V3h19.5v9.3M8.5 3v13M2 9.5h19.5");
}

.jv4-5y5ol {
  d: path("M8.5 9.5c-2-4-4.25-3.75-3.75-1.5C5 9.25 7 9.5 8.5 9.5Zm0 0c2-4 4.25-3.75 3.75-1.5C12 9.25 10 9.5 8.5 9.5Zm6.25 8.5l2 2L21 15.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
