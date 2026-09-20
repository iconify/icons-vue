<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u0jcrbcgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:arrow-shape-up-sharp" /></template>
<style>
.u0jcrbcgr {
  fill: currentColor;
  d: path("M8 21v-6H3l9-11l9 11h-5v6z");
}

</style>
