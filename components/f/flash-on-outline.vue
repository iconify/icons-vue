<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duy63e0pn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:flash-on-outline" /></template>
<style>
.duy63e0pn {
  fill: currentColor;
  d: path("m12 15.6l3.2-4.6h-2.85l2-7H9v8h3zM10 22v-8H7V2h10l-2 7h4zm2-10H9z");
}

</style>
