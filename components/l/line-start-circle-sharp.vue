<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x6qg_vbyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:line-start-circle-sharp" /></template>
<style>
.x6qg_vbyu {
  fill: currentColor;
  d: path("M8 16.423q-1.846 0-3.134-1.288Q3.577 13.846 3.577 12t1.289-3.134T8 7.577q1.73 0 2.97 1.127t1.416 2.796h8.537v1h-8.536q-.178 1.67-1.417 2.796Q9.73 16.423 8 16.423");
}

</style>
