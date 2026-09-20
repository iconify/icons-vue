<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vdvak-brn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:language-french-outline-sharp" /></template>
<style>
.vdvak-brn {
  fill: currentColor;
  d: path("M4 17V7h7v2H6v2h4v2H6v4zm9 0V7h6l1 1v4l-1 1h-.85L20 17h-2.1l-1.875-4H15v4zm2-6h3V9h-3z");
}

</style>
