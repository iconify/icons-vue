<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1sdyd2_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:create-new-folder-sharp" /></template>
<style>
.p1sdyd2_h {
  fill: currentColor;
  d: path("M3 19V5h6.596l2 2H21v12zm11.5-3.5h1v-2h2v-1h-2v-2h-1v2h-2v1h2z");
}

</style>
