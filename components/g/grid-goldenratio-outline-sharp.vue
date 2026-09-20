<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7h6winbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:grid-goldenratio-outline-sharp" /></template>
<style>
.p7h6winbq {
  fill: currentColor;
  d: path("M9 22v-7H2v-2h7v-2H2V9h7V2h2v7h2V2h2v7h7v2h-7v2h7v2h-7v7h-2v-7h-2v7zm2-9h2v-2h-2z");
}

</style>
