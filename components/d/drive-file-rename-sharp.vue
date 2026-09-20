<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yc55fxgkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:drive-file-rename-sharp" /></template>
<style>
.yc55fxgkb {
  fill: currentColor;
  d: path("M11.225 17H18v-2h-4.775zM6 17h3.075l7.575-7.55l-3.075-3.075L6 13.925zm7.575-6.6l-.95-.95l.95-.95l.925.925zM3 21V3h18v18z");
}

</style>
