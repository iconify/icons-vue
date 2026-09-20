<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lf5uyxb7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:hevc-sharp" /></template>
<style>
.lf5uyxb7o {
  fill: currentColor;
  d: path("M3.308 14.692V9.308h.884v2h1.616v-2h.884v5.384h-.884v-2.5H4.192v2.5zm4.961 0V9.308h2.885v.884h-2v1.116h2v.884h-2v1.616h2v.884zm5.27 0l-1.193-5.384h.904l1 4.461l1-4.461h.904l-1.193 5.384zm3.769 0V9.308h3.384v1.384h-.884v-.5h-1.616v3.616h1.616v-.5h.884v1.384z");
}

</style>
