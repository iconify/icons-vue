<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o_k518bmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:forum-outline-sharp" /></template>
<style>
.o_k518bmt {
  fill: currentColor;
  d: path("M6 18v-3h13V6h3v16l-4-4zm-4-1V2h15v11H6zm2-4.825L5.175 11H15V4H4zM4 11V4z");
}

</style>
