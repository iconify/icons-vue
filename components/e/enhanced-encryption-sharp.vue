<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ugutuvbmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:enhanced-encryption-sharp" /></template>
<style>
.ugutuvbmo {
  fill: currentColor;
  d: path("M11 16v3h2v-3h3v-2h-3v-3h-2v3H8v2zm-7 6V8h3V6q0-2.075 1.463-3.537T12 1t3.538 1.463T17 6v2h3v14zM9 8h6V6q0-1.25-.875-2.125T12 3t-2.125.875T9 6z");
}

</style>
