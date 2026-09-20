<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tgn1xpqgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:filter-8-sharp" /></template>
<style>
.tgn1xpqgj {
  fill: currentColor;
  d: path("M6.5 17V3h14v14zm-3 3V6.616h1V19h12.385v1zm8-10l-.5.5v4h5v-4l-.5-.5l.5-.5v-4h-5v4zM15 6.5v3h-3v-3zm0 4v3h-3v-3z");
}

</style>
