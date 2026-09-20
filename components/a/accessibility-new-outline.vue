<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_17r7bzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:accessibility-new-outline" /></template>
<style>
.q_17r7bzw {
  fill: currentColor;
  d: path("M10.799 5.316q-.491-.491-.491-1.2q0-.71.491-1.201q.492-.492 1.201-.492t1.201.492q.491.49.491 1.2t-.491 1.201q-.492.492-1.201.492t-1.201-.492M9.808 21.5V8.423q-1.558-.125-3.031-.346T4 7.539l.23-1q1.893.467 3.814.676q1.921.208 3.956.208t3.956-.209t3.813-.676l.231 1q-1.304.318-2.777.539t-3.03.346V21.5h-1v-6.23h-2.385v6.23z");
}

</style>
