<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6wkrww2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:heap-snapshot-thumbnail-outline-sharp" /></template>
<style>
.i6wkrww2w {
  fill: currentColor;
  d: path("M2.5 18V6h12v12zm14-7V6h5v5zm1-1h3V7h-3zm-14 7h10V7h-10zm13 1v-5h5v5zm1-1h3v-3h-3zm-14 0V7zm14-7V7zm0 7v-3zm-6.502-1.5q.416 0 .709-.291t.293-.707t-.291-.709t-.707-.293t-.709.291t-.293.707t.291.709t.707.293m-5.048-.261l5.789-5.789l-.689-.688l-5.788 5.788zm.048-4.739q.415 0 .709-.291T7 9.502t-.291-.709t-.707-.293t-.709.291T5 9.498t.291.709t.707.293");
}

</style>
