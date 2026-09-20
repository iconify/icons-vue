<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="isurmobgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:computer-arrow-up-sharp" /></template>
<style>
.isurmobgg {
  fill: currentColor;
  d: path("M11.48 14.27h1V9.574l2.12 2.114l.708-.708l-3.327-3.327l-3.289 3.288l.708.714l2.08-2.081zm-9.71 5.192v-1h20.46v1zm1.23-2v-13h18v13z");
}

</style>
