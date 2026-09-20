<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a7gqzdbdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:align-space-between-sharp" /></template>
<style>
.a7gqzdbdf {
  fill: currentColor;
  d: path("M7 7V4H2V2h20v2h-5v3zM2 22v-2h5v-3h10v3h5v2z");
}

</style>
