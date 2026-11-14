<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l2f8sjx_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:leaf-maple" /></template>
<style>
.l2f8sjx_c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13 3.875l.372.511A1.404 1.404 0 0 0 15 4.875a.57.57 0 0 1 .755.665L15.5 6.625a1.166 1.166 0 0 0 1.544 1.358l1.862-.698A.878.878 0 0 1 20 8.5l-.597 1.194A1.02 1.02 0 0 0 19.75 11a.638.638 0 0 1 .029 1.041l-2.425 1.818a1.425 1.425 0 0 0-.479 1.641a.667.667 0 0 1-.688.899l-4.045-.385a1.5 1.5 0 0 0-.284 0l-4.045.385a.667.667 0 0 1-.688-.899a1.425 1.425 0 0 0-.479-1.641l-2.425-1.818A.638.638 0 0 1 4.25 11a1.02 1.02 0 0 0 .347-1.306L4 8.5a.878.878 0 0 1 1.094-1.215l1.862.698A1.166 1.166 0 0 0 8.5 6.625L8.245 5.54A.57.57 0 0 1 9 4.875a1.404 1.404 0 0 0 1.628-.489L11 3.875a1.236 1.236 0 0 1 2 0M12 10v11.5");
}

</style>
