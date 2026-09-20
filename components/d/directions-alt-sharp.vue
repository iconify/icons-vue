<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dm46g0bog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:directions-alt-sharp" /></template>
<style>
.dm46g0bog {
  fill: currentColor;
  d: path("M12 22.8L1.2 12L12 1.2L22.8 12zm0-5.8l5-5l-5-5l-1.4 1.4l2.55 2.6H7v2h6.15l-2.55 2.6z");
}

</style>
