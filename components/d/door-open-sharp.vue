<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nua-dbf-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:door-open-sharp" /></template>
<style>
.nua-dbf-u {
  fill: currentColor;
  d: path("M4.462 20v-1H6V3.5h12V19h1.539v1zM15 19h2V4.5h-2zm-3.46-6.46q.23-.23.23-.54t-.23-.54t-.54-.23t-.54.23t-.23.54t.23.54t.54.23t.54-.23");
}

</style>
