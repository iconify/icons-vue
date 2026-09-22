<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7_vtebrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:edit-line-outline" /></template>
<style>
.p7_vtebrs {
  fill: currentColor;
  d: path("m9.896 20l1-1H21v1zM5 19h1.098L16.796 8.302l-1.098-1.098L5 17.902zm-1 1v-2.52L17.18 4.288q.122-.121.321-.204q.2-.083.413-.083q.188 0 .38.08q.193.078.352.212l1.068 1.074q.137.159.211.351Q20 5.91 20 6.1q0 .201-.08.4t-.207.326L6.52 20zM19.02 6.092l-1.112-1.111zm-2.782 1.67l-.54-.558l1.098 1.098z");
}

</style>
