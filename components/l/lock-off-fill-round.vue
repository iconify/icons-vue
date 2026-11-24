<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kc9xxeoyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-off-fill-round" /></template>
<style>
.kc9xxeoyc {
  fill: currentColor;
  d: path("m2.707 2.293l19 19a.999.999 0 1 1-1.414 1.414l-1.535-1.535A5 5 0 0 1 16 22H8a5 5 0 0 1-5-5v-4a4.99 4.99 0 0 1 3.001-4.584L1.293 3.707a.999.999 0 1 1 1.414-1.414M15 7a3 3 0 0 0-5.121-2.121a1 1 0 0 1-1.631-.325a1 1 0 0 1 .216-1.09A5.001 5.001 0 0 1 17 7v1.099A5.01 5.01 0 0 1 21 13v4q0 .356-.049.708L11.243 8H15Z");
}

</style>
