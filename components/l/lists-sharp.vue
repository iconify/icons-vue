<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cq2-7bw6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:lists-sharp" /></template>
<style>
.cq2-7bw6z {
  fill: currentColor;
  d: path("M3 19v-2.077h2.077V19zm4.846 0v-2.077H21V19zM3 13.038v-2.077h2.077v2.077zm4.846 0v-2.077H21v2.078zM3 7.077V5h2.077v2.077zm4.846 0V5H21v2.077z");
}

</style>
