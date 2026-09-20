<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vthtb6bda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:line-end-outline-sharp" /></template>
<style>
.vthtb6bda {
  fill: currentColor;
  d: path("M19.5 14.5q-.775 0-1.4-.425T17.2 13H2v-2h15.2q.275-.65.9-1.075t1.4-.425q1.05 0 1.775.725T22 12t-.725 1.775t-1.775.725");
}

</style>
