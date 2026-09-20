<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nuot_ab_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:format-image-front-outline" /></template>
<style>
.nuot_ab_r {
  fill: currentColor;
  d: path("M3 21v-2h18v2zm0-4v-2h2.5v2zm4 0V7h10v10zm11.5 0v-2H21v2zM9 15h6V9H9zm-6-2v-2h2.5v2zm15.5 0v-2H21v2zM3 9V7h2.5v2zm15.5 0V7H21v2zM3 5V3h18v2zm9 7");
}

</style>
