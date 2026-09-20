<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tuzj1fbuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bike-dock-outline-sharp" /></template>
<style>
.tuzj1fbuv {
  fill: currentColor;
  d: path("M4 20v-1l4.77-.917L9.807 4h4.384l1.039 14.083L20 19v1zm6.808-1.827h2.384V5h-2.384z");
}

</style>
