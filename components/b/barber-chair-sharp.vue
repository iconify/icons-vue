<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b4rc05ygp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:barber-chair-sharp" /></template>
<style>
.b4rc05ygp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 2.75h4v3h-4zm1.75 4.5l1.5 6.5h8.75m-7-3.5h6.5m.5 3.5l2 4.25h2.5M12 13.75v7.5m-4 0h8");
}

</style>
