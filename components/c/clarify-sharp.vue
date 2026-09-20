<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t7gpxtb0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:clarify-sharp" /></template>
<style>
.t7gpxtb0l {
  fill: currentColor;
  d: path("M6 17h7v-2H6zm10 0h2V7h-2zM6 13h7v-2H6zm0-4h7V7H6zM2 21V3h20v18z");
}

</style>
