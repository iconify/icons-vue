<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w670nibvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:home-storage-gear-sharp" /></template>
<style>
.w670nibvy {
  fill: currentColor;
  d: path("M5.5 8V7h13v1zm2-2.384v-1h9v1zm9.81 15.294l-.108-.885q-.473-.106-.89-.32q-.416-.215-.749-.588l-.834.335l-.538-.816l.688-.577q-.165-.517-.165-1.034t.165-1.035l-.688-.577l.538-.815l.835.335q.313-.374.739-.588t.899-.32l.108-.885h1l.107.885q.474.106.9.32q.425.214.739.588l.835-.335l.538.815l-.688.577q.165.518.165 1.035t-.165 1.035l.688.577l-.538.815l-.835-.335q-.333.373-.75.588q-.415.214-.889.32l-.107.885zm2.028-2.357q.625-.626.625-1.528t-.626-1.528t-1.528-.626t-1.527.626t-.626 1.528t.626 1.528t1.527.626t1.528-.626m-7.704.832H5.846l-1.673-10h15.654l-.233 1.276q-.479-.147-.867-.212t-.918-.064q-2.77 0-4.705 1.934q-1.935 1.935-1.935 4.706q0 .564.117 1.198q.118.635.347 1.162");
}

</style>
