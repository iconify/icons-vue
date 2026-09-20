<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n24o--baw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:files-sharp" /></template>
<style>
.n24o--baw {
  fill: currentColor;
  d: path("M2 20v-5h11V4h9v16zm0-6V6h8zm3.825-1L11 7.825V13z");
}

</style>
