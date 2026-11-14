<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n1jwmmdss"/><path class="o-mzdcfmx"/><path class="uqq4e9bxc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:blood-bag" /></template>
<style>
.n1jwmmdss {
  d: path("M6 2.5h12a1 1 0 0 1 1 1v13a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1v-13a1 1 0 0 1 1-1Zm4.5 2.75h3");
}

.o-mzdcfmx {
  fill: currentColor;
  d: path("M12 8c1.75 2 2.75 3.25 2.75 4.5C14.75 14 13.5 15 12 15s-2.75-1-2.75-2.5c0-1.25 1-2.5 2.75-4.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uqq4e9bxc {
  d: path("M10 17.5v4m4-4v4");
}

</style>
