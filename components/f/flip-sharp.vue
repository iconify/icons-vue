<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hx0gb20rn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:flip-sharp" /></template>
<style>
.hx0gb20rn {
  fill: currentColor;
  d: path("M15.077 5.23V4h1.23v1.23zm0 14.77v-1.23h1.23V20zm3.692-14.77V4H20v1.23zm0 14.77v-1.23H20V20zm0-3.692v-1.231H20v1.23zm0-3.693v-1.23H20v1.23zm0-3.692v-1.23H20v1.23zM8.923 20H4V4h4.923v1H5v14h3.923zm2.577 3V1.385h1V23z");
}

</style>
