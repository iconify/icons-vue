<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_3duj87p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:home-speaker" /></template>
<style>
.l_3duj87p {
  fill: currentColor;
  d: path("m6.2 12l.775-5.825q.05-.275.213-.488t.412-.312l7.9-3.15q.45-.2.875.063t.475.762L17.925 12zm3.375 9Q7.75 21 6.55 19.638t-.95-3.163L5.925 14H18.15l.3 2.525q.2 1.8-.975 3.138T14.5 21z");
}

</style>
