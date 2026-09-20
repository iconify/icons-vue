<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n1oxuvbxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:cake-add-sharp" /></template>
<style>
.n1oxuvbxy {
  fill: currentColor;
  d: path("M2 22v-7h18v7zm2-9V8h6V6.55q-.45-.3-.725-.725T9 4.8q0-.375.15-.738T9.6 3.4L11 2l1.4 1.4q.3.3.45.662T13 4.8q0 .6-.275 1.025T12 6.55V8h6v5zm15-5V6h-2V4h2V2h2v2h2v2h-2v2z");
}

</style>
