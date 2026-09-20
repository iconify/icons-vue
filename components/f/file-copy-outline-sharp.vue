<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pyu_43zvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:file-copy-outline-sharp" /></template>
<style>
.pyu_43zvz {
  fill: currentColor;
  d: path("M7 18V2h8.5L20 6.5V18zm8-11V3H8v14h11V7zM3 22V8h1v13h10v1zM8 3v4zv14z");
}

</style>
