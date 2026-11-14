<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="htia-9bey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:loppers" /></template>
<style>
.htia-9bey {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 9.5Q18 9 17.5 3M12 9.5Q6 9 6.5 3M12 9.5L8.25 15M12 9.5l3.75 5.5m-8.852-.752l2.516 1.634l-3.812 5.87l-2.516-1.634Zm7.688 1.634l2.516-1.634l3.812 5.87l-2.516 1.634Z");
}

</style>
