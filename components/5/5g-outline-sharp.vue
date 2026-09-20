<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5nsw9bgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:5g-outline-sharp" /></template>
<style>
.o5nsw9bgs {
  fill: currentColor;
  d: path("M3 17v-2h5v-2H3V7h7v2H5v2h5v6zm18-6v6h-9V7h9v2h-7v6h5v-2h-2.5v-2z");
}

</style>
