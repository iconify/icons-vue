<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzhdenbpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:directions-alt-sharp" /></template>
<style>
.mzhdenbpg {
  fill: currentColor;
  d: path("M12 21.377L2.623 12L12 2.623L21.377 12zm0-5.07L16.308 12L12 7.692l-.708.708l3.089 3.1H7.692v1h6.689l-3.089 3.1z");
}

</style>
