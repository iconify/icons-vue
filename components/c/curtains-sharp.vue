<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a5cx2ac4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:curtains-sharp" /></template>
<style>
.a5cx2ac4w {
  fill: currentColor;
  d: path("M2 21v-2h2V3h16v16h2v2zm6.225-9q1.7 1.125 2.625 3.075T11.95 19h.1q.175-1.975 1.1-3.925T15.775 12q-1.7-1.125-2.625-3.075T12.05 5h-.1q-.175 1.975-1.1 3.925T8.225 12");
}

</style>
