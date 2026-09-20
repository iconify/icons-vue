<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d5911o9vi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:arrow-drop-up-sharp" /></template>
<style>
.d5911o9vi {
  fill: currentColor;
  d: path("m7 14l5-5l5 5z");
}

</style>
