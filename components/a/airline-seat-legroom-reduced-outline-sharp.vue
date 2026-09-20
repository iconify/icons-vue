<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-58ddbtu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:airline-seat-legroom-reduced-outline-sharp" /></template>
<style>
.a-58ddbtu {
  fill: currentColor;
  d: path("M14.116 20.23v-1.69l1.307-4.039H5.769v-11h5v7h6.847l.776 1.064l-2.276 6.975h2.692v1.692zm-2.347-3.73h-8v-13h1v12h7z");
}

</style>
