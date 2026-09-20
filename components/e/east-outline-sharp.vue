<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="whik5k-ps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:east-outline-sharp" /></template>
<style>
.whik5k-ps {
  fill: currentColor;
  d: path("m14.673 18.327l-.713-.688l5.157-5.158H3v-1h16.137l-5.152-5.158l.688-.688l6.346 6.346z");
}

</style>
