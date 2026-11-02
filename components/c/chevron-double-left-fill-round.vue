<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3xt6ccoj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chevron-double-left-fill-round" /></template>
<style>
.i3xt6ccoj {
  fill: currentColor;
  d: path("m8.414 12l3.293 3.293a.999.999 0 1 1-1.414 1.414l-4-4a.997.997 0 0 1 0-1.414l4-4a.999.999 0 1 1 1.414 1.414Zm6 0l3.293 3.293a.999.999 0 1 1-1.414 1.414l-4-4a1 1 0 0 1 0-1.414l4-4a.999.999 0 1 1 1.414 1.414Z");
}

</style>
