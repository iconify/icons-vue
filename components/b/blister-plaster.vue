<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-gvdnfwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:blister-plaster" /></template>
<style>
.x-gvdnfwg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.879 4.222l9.899 9.899a2 2 0 0 1 0 2.829l-2.828 2.828a2 2 0 0 1-2.829 0L4.222 9.879a2 2 0 0 1 0-2.829L7.05 4.222a2 2 0 0 1 2.829 0Zm3.182 3.182l-5.657 5.657m9.192-2.122l-5.657 5.657M7.75 7.75h.01m8.49 8.5h.01");
}

</style>
