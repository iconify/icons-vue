<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rkk21fb5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-text-overflow-outline-rounded" /></template>
<style>
.rkk21fb5j {
  fill: currentColor;
  d: path("M5.393 19.356Q5.25 19.213 5.25 19V5q0-.213.144-.356t.357-.144t.356.144T6.25 5v14q0 .213-.144.356t-.357.144t-.356-.144M12.24 8.587q-.144-.144-.144-.356V5q0-.213.144-.356q.144-.144.357-.144t.356.144t.143.356v3.23q0 .213-.144.357t-.356.144t-.356-.144m4.031 5.892q-.14.146-.335.146t-.359-.146q-.146-.165-.146-.363t.146-.345l1.271-1.271H9.519q-.212 0-.356-.144t-.144-.357t.144-.356t.356-.143h7.329l-1.271-1.271q-.146-.148-.146-.345t.146-.363t.347-.165t.347.165l1.913 1.913q.243.243.243.566t-.242.565zm-4.031 4.877q-.144-.144-.144-.356v-3.23q0-.213.144-.357t.357-.144t.356.144t.143.356V19q0 .213-.144.356t-.356.144t-.356-.144");
}

</style>
