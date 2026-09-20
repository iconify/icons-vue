<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b02uf93_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:align-justify-flex-start-outline-sharp" /></template>
<style>
.b02uf93_l {
  fill: currentColor;
  d: path("M2 22V2h2v20zm11-5V7h3v10zm-6 0V7h3v10z");
}

</style>
