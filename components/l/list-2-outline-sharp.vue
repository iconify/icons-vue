<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c2drsmbzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:list-2-outline-sharp" /></template>
<style>
.c2drsmbzt {
  fill: currentColor;
  d: path("M7.75 17v-1h8.5v1zM4 12.5v-1h16v1zM7.75 8V7h8.5v1z");
}

</style>
