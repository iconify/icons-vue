<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gt8h3ibnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:download-sharp" /></template>
<style>
.gt8h3ibnz {
  fill: currentColor;
  d: path("m12 15.577l-3.539-3.538l.708-.72L11.5 13.65V5h1v8.65l2.33-2.33l.709.719zM5 19v-4.038h1V18h12v-3.038h1V19z");
}

</style>
