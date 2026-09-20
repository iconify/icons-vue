<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="juy7new6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:clarify-outline-sharp" /></template>
<style>
.juy7new6l {
  fill: currentColor;
  d: path("M6 17h7v-2H6zm10 0h2V7h-2zM6 13h7v-2H6zm0-4h7V7H6zM2 21V3h20v18zm2-2h16V5H4zm0 0V5z");
}

</style>
