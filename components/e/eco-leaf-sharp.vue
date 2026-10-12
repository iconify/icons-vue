<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ewgypyb9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:eco-leaf-sharp" /></template>
<style>
.ewgypyb9l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75C16.25 6 18.25 9.5 18.25 13a6.25 6.25 0 0 1-12.5 0c0-3.5 2-7 6.25-10.25ZM12 8v11.25m0 0v2m0-8l2.5-2M12 16.5l-2.5-2");
}

</style>
