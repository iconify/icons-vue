<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="esephx4ku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:desktop-landscape-add-outline-sharp" /></template>
<style>
.esephx4ku {
  fill: currentColor;
  d: path("M4 18V6zm2.385-2.384v-4.462h8.461v4.462zM3 19V5h18v7.385h-1V6H4v12h9v1zm13.73-6.616V9.27H9v-.885h8.616v4zM18 21v-2.616h-2.615v-1H18V14.77h1v2.615h2.616v1H19V21z");
}

</style>
