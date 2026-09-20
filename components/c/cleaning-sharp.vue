<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mamjj4b7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:cleaning-sharp" /></template>
<style>
.mamjj4b7a {
  fill: currentColor;
  d: path("m9 7l1-2V4H9V2h7v2l-1 2h-3V5l-2 2zM8 22v-7.425L12 7h4v15z");
}

</style>
