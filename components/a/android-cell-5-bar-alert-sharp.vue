<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j1aqu_r8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:android-cell-5-bar-alert-sharp" /></template>
<style>
.j1aqu_r8z {
  fill: currentColor;
  d: path("M1 20v-6h3v6zm4.75 0v-8h3v8zm4.75 0V9h3v11zm10.788-.288Q21 19.426 21 19t.288-.712T22 18t.713.288T23 19t-.288.713T22 20t-.712-.288M21 17v-3.5h2V17zm-1-4.825V4h3v7.85q-.25-.05-.488-.075T22 11.75q-.525 0-1.037.113t-.963.312M15.25 20V7h3v6.45q-.6.675-.925 1.525T17 16.725t.313 1.75T18.2 20z");
}

</style>
