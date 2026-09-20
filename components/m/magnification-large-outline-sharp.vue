<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mo2c33bvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:magnification-large-outline-sharp" /></template>
<style>
.mo2c33bvl {
  fill: currentColor;
  d: path("M5.5 14.5h11v-7h-11zM3 19V5h18v14zm1-1h16V6H4zm0 0V6z");
}

</style>
