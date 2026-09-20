<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="gp6zlwbrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:attach-28-filled" /></template>
<style>
.gp6zlwbrg {
  fill: currentColor;
  d: path("M22.042 5.475a5.01 5.01 0 0 0-7.087-.007L3.707 16.708a1 1 0 1 1-1.414-1.415l11.249-11.24a7.009 7.009 0 1 1 9.906 9.918L12.623 24.782a4.178 4.178 0 0 1-5.907-5.91L17.543 8.043a1 1 0 0 1 1.414 1.414L8.13 20.287a2.178 2.178 0 0 0 3.08 3.08l10.825-10.811a5.01 5.01 0 0 0 .007-7.081");
}

</style>
