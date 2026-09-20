<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ogngubq9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:event-seat-outline-sharp" /></template>
<style>
.ogngubq9y {
  fill: currentColor;
  d: path("M4.5 20.308v-5h15v5h-1v-4h-13v4zM4 13.654v-2h2v2zm3.77-.116v-9.73h8.46v9.73zm10.23.116v-2h2v2zm-9.23-1.115h6.46V4.808H8.77zm0 0h6.46z");
}

</style>
