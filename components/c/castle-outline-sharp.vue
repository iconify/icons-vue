<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e942_zb8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:castle-outline-sharp" /></template>
<style>
.e942_zb8c {
  fill: currentColor;
  d: path("M1.5 20.5v-11h1v2h3v-8h1v2h3v-2h1v2h3v-2h1v2h3v-2h1v8h3v-2h1v11h-8v-5h-5v5zm1-1h6v-5h7v5h6v-7h-4v-6h-11v6h-4zm7-8h1V9.308h-1zm4 0h1V9.308h-1zM12 13");
}

</style>
