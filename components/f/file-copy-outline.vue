<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kaxrilgml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:file-copy-outline" /></template>
<style>
.kaxrilgml {
  fill: currentColor;
  d: path("M19 19H8q-.825 0-1.412-.587T6 17V3q0-.825.588-1.412T8 1h7l6 6v10q0 .825-.587 1.413T19 19M14 8V3H8v14h11V8zM4 23q-.825 0-1.412-.587T2 21V7h2v14h11v2zM8 3v5zv14z");
}

</style>
