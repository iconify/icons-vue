<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b4hkbvxly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:handcuffs-sharp" /></template>
<style>
.b4hkbvxly {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 13.48v-2.23h2.5v2.23a3.5 3.5 0 1 1-2.5 0Zm11.5 0v-2.23H19v2.23a3.5 3.5 0 1 1-2.5 0ZM6.25 11.25V9.5m11.5 1.75V9.5M9.81 5.71h4.38m-4.38 0A2.6 1.5-46.74 1 1 6.25 9.5a2.6 1.5-46.74 1 1 3.56-3.79Zm7.94 3.79a2.6 1.5 46.74 1 1-3.56-3.79a2.6 1.5 46.74 1 1 3.56 3.79Z");
}

</style>
