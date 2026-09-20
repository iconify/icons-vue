<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ohi3oqbqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:clarify-outline-sharp" /></template>
<style>
.ohi3oqbqy {
  fill: currentColor;
  d: path("M6.5 16.5h6v-1h-6zm10 0h1v-9h-1zm-10-4h6v-1h-6zm0-4h6v-1h-6zM3 20V4h18v16zm1-1h16V5H4zm0 0V5z");
}

</style>
