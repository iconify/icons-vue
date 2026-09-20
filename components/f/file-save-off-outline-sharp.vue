<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p2_o2pvrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:file-save-off-outline-sharp" /></template>
<style>
.p2_o2pvrc {
  fill: currentColor;
  d: path("m20.9 18.1l-1.4-1.425l1.1-1.1L22 17zM19 16.175l-2-2V13h2zM14 24v-2h5.175L6 8.825V18h6v2H4V6.825L.7 3.5l1.4-1.4L22 22v2zm3-13h2V8l-6-6H4.8l2.025 2H12v5h5zm-4.025-.85");
}

</style>
