<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ccmaxdsxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:auto-awesome-motion-sharp" /></template>
<style>
.ccmaxdsxo {
  fill: currentColor;
  d: path("M11 21V11h10v10zm-4-3.77V7h10.23v1H8v9.23zm-4-4V3h10.23v1H4v9.23z");
}

</style>
