<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jpzgg8bby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:eject-outline-sharp" /></template>
<style>
.jpzgg8bby {
  fill: currentColor;
  d: path("M6.154 18.346v-.923h11.692v.923zm.158-3.692L12 6.154l5.689 8.5zm1.815-.923h7.746L12 7.946z");
}

</style>
