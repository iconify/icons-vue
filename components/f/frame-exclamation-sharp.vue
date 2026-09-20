<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="am973fvlz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:frame-exclamation-sharp" /></template>
<style>
.am973fvlz {
  fill: currentColor;
  d: path("M11.5 14.077v-8h1v8zm0 3.846v-1h1v1zM2 22v-4.23h1V21h3.23v1zm15.77 0v-1H21v-3.23h1V22zM2 6.23V2h4.23v1H3v3.23zm19 0V3h-3.23V2H22v4.23z");
}

</style>
