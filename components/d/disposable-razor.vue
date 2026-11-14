<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-_zmualw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:disposable-razor" /></template>
<style>
.p-_zmualw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.884 4.045l7.071 7.071l-2.475 2.475l-7.071-7.071Zm1.061 6.01L12.53 11.47m-.884-.884l1.768 1.768l-7.424 7.424l-1.768-1.768Zm1.415-3.889l4.242 4.242");
}

</style>
