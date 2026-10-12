<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="exdkp3bed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:herb-sharp" /></template>
<style>
.exdkp3bed {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 8c-1.5-1.5-1.5-3.75 0-5.25c1.5 1.5 1.5 3.75 0 5.25Zm0 3.5c-.25-2.75-2.25-4-5.25-4c.25 2.75 2.25 4 5.25 4Zm0 0c.25-2.75 2.25-4 5.25-4c-.25 2.75-2.25 4-5.25 4Zm0 6c-.75-2.75-3-4.25-6.25-4c.5 3 2.75 4.5 6.25 4Zm0 0c.75-2.75 3-4.25 6.25-4c-.5 3-2.75 4.5-6.25 4Zm0 3.75V8");
}

</style>
