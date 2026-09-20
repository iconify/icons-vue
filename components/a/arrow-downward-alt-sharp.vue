<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ev7s88b2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrow-downward-alt-sharp" /></template>
<style>
.ev7s88b2g {
  fill: currentColor;
  d: path("M12 17.308L6.692 12l.708-.708l4.1 4.1V5.5h1v9.892l4.1-4.1l.708.708z");
}

</style>
