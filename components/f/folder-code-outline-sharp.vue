<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zmli49y8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:folder-code-outline-sharp" /></template>
<style>
.zmli49y8d {
  fill: currentColor;
  d: path("M4 18V6v13zm-2 2V4h8l2 2h10v7h-2V8h-8.825l-2-2H4v12h5v2zm12.6 2.6L11 19l3.6-3.6l1.4 1.425L13.825 19L16 21.175zm4.8 0L18 21.175L20.175 19L18 16.825l1.4-1.425L23 19z");
}

</style>
