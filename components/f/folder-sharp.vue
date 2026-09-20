<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ohawklu8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:folder-sharp" /></template>
<style>
.ohawklu8u {
  fill: currentColor;
  d: path("M3 19V5h6.596l2 2H21v12z");
}

</style>
