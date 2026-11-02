<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zfxqjccim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hourglass-fill" /></template>
<style>
.zfxqjccim {
  fill: currentColor;
  d: path("M5 2h14a1 1 0 0 1 0 2h-1v2c0 1.039-.578 1.992-1.293 2.707L13.414 12l3.293 3.293C17.422 16.008 18 16.961 18 18v2h1a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2h1v-2c0-1.039.578-1.992 1.293-2.707L10.586 12L7.293 8.707C6.578 7.992 6 7.039 6 6V4H5a1 1 0 0 1 0-2");
}

</style>
