<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oy4vudwmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:display-add-sharp" /></template>
<style>
.oy4vudwmy {
  fill: currentColor;
  d: path("M18 9V6h-3V5h3V2h1v3h3v1h-3v3zM9 20v-2H3V4h9.812q-.098.36-.147.74q-.05.38-.05.78q0 2.443 1.711 4.154q1.71 1.71 4.155 1.71q.683 0 1.314-.145q.632-.145 1.205-.424V18h-6v2z");
}

</style>
