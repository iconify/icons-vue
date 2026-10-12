<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o9f-9qb8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:iceberg-sharp" /></template>
<style>
.o9f-9qb8p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10.58 3.25l2.09 3.25l.33.5l.51.31l.23.13l.51.31l.29.52l.67 1.21q.29.52.7.96l3.18 3.37l.41.44l-.21.56l-1.83 4.88l-.21.56l-.59.09l-5.57.82l-.59.09l-.52-.31l-4.46-2.63L5 18l-.07-.6l-.36-3.3l-.07-.6l.37-.47l2.01-2.56q.37-.47.64-1.01l.71-1.42q.27-.54.48-1.1l1.33-3.63l.21-.56zm-7.83 8.5h18.5");
}

</style>
