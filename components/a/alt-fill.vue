<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l28qlsili"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:alt-fill" /></template>
<style>
.l28qlsili {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 21H6.7003C7.4906 21 8.2069 20.534 8.5279 19.812L15.4721 4.188C15.7931 3.465 16.5094 3 17.2997 3H21M13 21H21");
}

</style>
