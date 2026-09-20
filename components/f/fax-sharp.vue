<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cisxgrbhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:fax-sharp" /></template>
<style>
.cisxgrbhd {
  fill: currentColor;
  d: path("M7.539 19.5v-10h.769V4.846h9V9.5h3.23v10zm-4.654 1h3.884v-12H2.885zm6.423-11h7V5.846h-7zm-.27 7.5h4v-5h-4zm5-3h2v-2h-2zm2.808 0h2v-2h-2zm-2.808 3h2v-2h-2zm2.808 0h2v-2h-2z");
}

</style>
