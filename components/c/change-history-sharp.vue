<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="etyl813nq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:change-history-sharp" /></template>
<style>
.etyl813nq {
  fill: currentColor;
  d: path("M3.808 19L12 5.885L20.192 19z");
}

</style>
