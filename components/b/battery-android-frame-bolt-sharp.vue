<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdfa4n-bo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-android-frame-bolt-sharp" /></template>
<style>
.bdfa4n-bo {
  fill: currentColor;
  d: path("M2 17V7h15.723l-.792 1H3v8h12.998l-.202 1zm15.867-.77l.604-3.384h-2.855l4.069-5.077h.448l-.604 3.385h2.856l-4.07 5.077zM4.385 14.617V9.385h11.438l-4.184 5.23z");
}

</style>
