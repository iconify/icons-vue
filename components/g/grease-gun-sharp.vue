<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="grjqopruv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:grease-gun-sharp" /></template>
<style>
.grjqopruv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 6.5h11.75v6H9.5zm6 0v6m-8.75-7H9.5v8H5.75v-8zm-.25 0L9 3h9M5.75 11h-3v10.25");
}

</style>
