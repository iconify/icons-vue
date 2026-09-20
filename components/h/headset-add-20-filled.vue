<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="caqfvqb9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:headset-add-20-filled" /></template>
<style>
.caqfvqb9c {
  fill: currentColor;
  d: path("M19 5.5a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0m-4-2a.5.5 0 0 0-1 0V5h-1.5a.5.5 0 0 0 0 1H14v1.5a.5.5 0 0 0 1 0V6h1.5a.5.5 0 0 0 0-1H15zm-.5 7.5a5.5 5.5 0 0 0 1.5-.207V11a2 2 0 0 1-2 2h-1a1 1 0 0 1-1-1v-1.6c.75.384 1.6.6 2.5.6m-4.247-8.995a5.5 5.5 0 0 0-.662 1.011A5 5 0 0 0 5 8h2a1 1 0 0 1 1 1v3a1 1 0 0 1-1 1H5v1a2 2 0 0 0 2 2h1a2 2 0 1 1 .268 1H7a3 3 0 0 1-3-3V8a6 6 0 0 1 6.253-5.995");
}

</style>
