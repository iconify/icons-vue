<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="horfd6i1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:edit-outline-sharp" /></template>
<style>
.horfd6i1v {
  fill: currentColor;
  d: path("M5 19h1.425L16.2 9.225L14.775 7.8L5 17.575zm-2 2v-4.25L17.625 2.175L21.8 6.45L7.25 21zM19 6.4L17.6 5zm-3.525 2.125l-.7-.725L16.2 9.225z");
}

</style>
