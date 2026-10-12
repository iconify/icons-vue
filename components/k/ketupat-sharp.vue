<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fpk_xj6ix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ketupat-sharp" /></template>
<style>
.fpk_xj6ix {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.85 6.91l5.3 5.68l.85.91l-.85.91l-5.3 5.68L12 21l-.85-.91l-5.3-5.68L5 13.5l.85-.91l5.3-5.68L12 6zM9.4 10.75l5.2 5.5m0-5.5l-5.2 5.5M12 6V3.563l3.25-.813M12 6l-.737-2.211L8.5 3");
}

</style>
