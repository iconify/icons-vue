<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dywoibbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-user-corner-fill" /></template>
<style>
.dywoibbzu {
  fill: currentColor;
  d: path("M17.714 9H10a.997.997 0 0 0-1 1v11a1 1 0 0 1-1 1H6a3 3 0 0 1-3-3v-8.092c0-.866.373-1.689 1.024-2.258l6-5.25a3 3 0 0 1 3.952 0l4.397 3.847A1.001 1.001 0 0 1 17.714 9M14 14a3 3 0 1 1 6 0a3 3 0 0 1-6 0m2 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0m-3 7c0-.468.141-.92.391-1.314c1.425-2.245 5.793-2.245 7.218 0c.25.394.391.846.391 1.314a1 1 0 0 1-2 0a.46.46 0 0 0-.08-.243c-.21-.331-.661-.535-1.024-.637A3.3 3.3 0 0 0 17 20a3.3 3.3 0 0 0-.896.12c-.363.102-.814.306-1.024.637A.46.46 0 0 0 15 21a1 1 0 0 1-2 0");
}

</style>
