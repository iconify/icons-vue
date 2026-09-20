<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bon5nnb_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:language-gb-english-sharp" /></template>
<style>
.bon5nnb_q {
  fill: currentColor;
  d: path("M14 15.5h4.23l.674-.673v-1.654l-.673-.673H14zm0-4h4.23l.674-.673V9.173L18.23 8.5H14zm-9.904 5v-9h6.77v1h-5.77v7H10v-3H7.808v-1H11v5zm8.904 0v-9h5.692l1.212 1.212v2.346l-.904.904l.904.904v2.423L18.692 16.5z");
}

</style>
