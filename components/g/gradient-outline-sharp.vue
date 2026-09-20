<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c3cbbpb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:gradient-outline-sharp" /></template>
<style>
.c3cbbpb2c {
  fill: currentColor;
  d: path("M11 13v-2h2v2zm-2 2v-2h2v2zm4 0v-2h2v2zm2-2v-2h2v2zm-8 0v-2h2v2zm-3 7V4h16v16zm3-1h2v-2H7zm4 0h2v-2h-2zm8 0v-2zM5 17h2v-2h2v2h2v-2h2v2h2v-2h2v2h2v-2h-2v-2h2V5H5v8h2v2H5zm0 2V5zm14-6v2zm-4 4v2h2v-2z");
}

</style>
