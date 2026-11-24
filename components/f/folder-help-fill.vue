<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wyqla8b4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-help-fill" /></template>
<style>
.wyqla8b4k {
  fill: currentColor;
  d: path("M12.414 5H19a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h5c.265 0 .52.105.707.293Zm-3.178 5.832A3 3 0 0 0 9 12a1 1 0 0 0 2 0a1.001 1.001 0 0 1 1.707-.707a1 1 0 0 1 .215 1.094A.99.99 0 0 1 12 13a1 1 0 0 0 0 2a3 3 0 1 0-2.764-4.168M12.01 16H12a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
