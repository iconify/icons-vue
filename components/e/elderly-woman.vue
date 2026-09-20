<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h813ypq9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:elderly-woman" /></template>
<style>
.h813ypq9m {
  fill: currentColor;
  d: path("m7 22.692l-.812-.584l2.562-3.685H6.73q.155-1.952.613-4.041t1.155-3.834q.696-1.77 1.599-2.89t1.907-1.12q.656 0 1.028.431t.874 1.273q.8 1.35 1.498 2.044q.698.695 1.698 1.314q.179-.258.446-.39q.268-.133.6-.133q.587 0 .979.392t.392.954v10.27h-.769v-10.27q0-.238-.17-.407q-.168-.17-.407-.17t-.408.17t-.169.407v.654h-.769v-.475q-1.008-.64-2.027-1.641t-1.61-2.04l-.92 4.098l2.018 5.148v4.525h-1v-4.269H10zm6.289-17.5q-.691 0-1.192-.5q-.5-.501-.5-1.192q0-.084.08-.504q-.217-.105-.36-.305q-.144-.199-.144-.46q0-.367.24-.607t.606-.24q.262 0 .46.144q.2.143.306.36q.13-.05.251-.065q.122-.015.253-.015q.69 0 1.19.5q.502.502.502 1.192t-.501 1.191t-1.191.501");
}

</style>
