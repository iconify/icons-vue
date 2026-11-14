<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ei5wthb5f"/><path class="o-4x2-hdx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ball-peen-hammer" /></template>
<style>
.ei5wthb5f {
  d: path("m12.707 2.808l6.364 6.364l-3.182 3.182L9.525 5.99Z");
}

.o-4x2-hdx {
  d: path("m12.707 9.172l2.121 2.121l-8.838 8.839l-2.122-2.122Zm4.043 3.078a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
