<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hcz140bfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:host-sharp" /></template>
<style>
.hcz140bfk {
  fill: currentColor;
  d: path("M2 21V3h9v18zm11 0V3h9v18zm-8-6h3v-2H5zm11 0h3v-2h-3zM5 12h3v-2H5zm11 0h3v-2h-3zM5 9h3V7H5zm11 0h3V7h-3z");
}

</style>
