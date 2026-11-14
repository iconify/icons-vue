<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xp1v7lbqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:balance-equal" /></template>
<style>
.xp1v7lbqw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 11v9.5m-4 0h8M4 11h16M3 7.5h6m-3 0V11m9-3.5h6m-3 0V11M4 3h4v4.5H4Zm12 0h4v4.5h-4Z");
}

</style>
