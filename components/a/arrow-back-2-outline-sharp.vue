<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k5hlx-bla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:arrow-back-2-outline-sharp" /></template>
<style>
.k5hlx-bla {
  fill: currentColor;
  d: path("M16 19L5 12l11-7zm-2-3.65v-6.7L8.75 12z");
}

</style>
