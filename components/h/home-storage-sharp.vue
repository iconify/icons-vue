<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zh03iabhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:home-storage-sharp" /></template>
<style>
.zh03iabhb {
  fill: currentColor;
  d: path("m5.846 19.385l-1.673-10h15.654l-1.673 10zm3.654-5.5h5v-1h-5zM5.5 8V7h13v1zm2-2.384v-1h9v1z");
}

</style>
