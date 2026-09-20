<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzm4vobuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:library-add-sharp" /></template>
<style>
.lzm4vobuu {
  fill: currentColor;
  d: path("M13 13.5h1v-3h3v-1h-3v-3h-1v3h-3v1h3zM6.5 17V3h14v14zm-3 3V6.616h1V19h12.385v1z");
}

</style>
