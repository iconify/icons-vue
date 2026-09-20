<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="muoearq5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:home-storage-gear-outline-sharp" /></template>
<style>
.muoearq5k {
  fill: currentColor;
  d: path("M5.5 8V7h13v1zm2-2.384v-1h9v1zm-2.1 4.769l.34 2.111q.34 2.112.935 5.889zm6.233 9H5.846l-1.673-10h15.654l-.177 1H5.4l1.275 8h4.646q.056.28.132.52q.076.241.18.48m5.677 1.525l-.108-.885q-.473-.106-.89-.32q-.416-.215-.749-.588l-.834.335l-.538-.816l.688-.577q-.165-.517-.165-1.034t.165-1.035l-.688-.577l.538-.815l.835.335q.313-.374.739-.588t.899-.32l.108-.885h1l.107.885q.474.106.9.32q.425.214.739.588l.835-.335l.538.815l-.688.577q.165.518.165 1.035t-.165 1.035l.688.577l-.538.815l-.835-.335q-.333.373-.75.588q-.415.214-.889.32l-.107.885zm2.028-2.357q.625-.626.625-1.528t-.626-1.528t-1.528-.626t-1.527.626t-.626 1.528t.626 1.528t1.527.626t1.528-.626");
}

</style>
