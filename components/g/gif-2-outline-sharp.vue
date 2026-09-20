<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sg261ubsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:gif-2-outline-sharp" /></template>
<style>
.sg261ubsn {
  fill: currentColor;
  d: path("M2 17V7h8v2H4v6h4v-2H6v-2h4v6zm10 0V7h2v10zm4 0V7h7v2h-5v2h4v2h-4v4z");
}

</style>
