<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lco8f9_hn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:eraser-size-3-rounded" /></template>
<style>
.lco8f9_hn {
  fill: currentColor;
  d: path("M8.807 18q-1.163 0-1.985-.817T6 15.209q0-.538.213-1.056q.214-.518.62-.916l6.404-6.423q.399-.397.918-.606q.52-.208 1.06-.208q1.158 0 1.972.817T18 8.791q0 .538-.208 1.056q-.209.518-.606.917l-6.403 6.423q-.423.404-.93.608T8.808 18");
}

</style>
