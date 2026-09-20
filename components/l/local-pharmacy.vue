<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xl1viv46j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:local-pharmacy" /></template>
<style>
.xl1viv46j {
  fill: currentColor;
  d: path("M3 21v-2l2-6l-2-6V5h12.7l1.45-4l2.35.85L18.35 5H21v2l-2 6l2 6v2zm8-4h2v-3h3v-2h-3V9h-2v3H8v2h3z");
}

</style>
