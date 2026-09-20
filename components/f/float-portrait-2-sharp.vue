<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o3wf_qb2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:float-portrait-2-sharp" /></template>
<style>
.o3wf_qb2l {
  fill: currentColor;
  d: path("M8 11h6V6H8zm12 11H4V2h16z");
}

</style>
