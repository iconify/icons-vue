<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t99v2obmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:altitude" /></template>
<style>
.t99v2obmp {
  fill: currentColor;
  d: path("M18.5 12V7.108l-2.1 2.08l-.688-.688L19 5.212L22.288 8.5l-.688.714l-2.1-2.1V12zM2.904 20.192l4.192-5.615l3.462 4.615l.792-.604l-1.523-2.03l4.27-5.712l7 9.346z");
}

</style>
