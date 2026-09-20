<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z1scfnx-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:agents-20-filled" /></template>
<style>
.z1scfnx-w {
  fill: currentColor;
  d: path("M10.669 2a3 3 0 0 0-.665 1.227l-3.438 12.89a.501.501 0 0 0 .967.258l3.438-12.89a2 2 0 0 1 1.81-1.48a3 3 0 0 1 2.375 1.394l3.574 5.667c.36.57.36 1.297 0 1.868l-3.941 6.25a1.75 1.75 0 0 1-1.48.816H9.333c.307-.343.54-.759.664-1.227L13.435 3.88a.5.5 0 0 0-.965-.258L9.03 16.516a2 2 0 0 1-1.813 1.48A3 3 0 0 1 4.84 16.6l-3.574-5.667a1.75 1.75 0 0 1 0-1.868l3.941-6.25a1.75 1.75 0 0 1 1.48-.816z");
}

</style>
