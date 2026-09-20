<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-fxrg6hz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:crop-2-3-sharp" /></template>
<style>
.f-fxrg6hz {
  fill: currentColor;
  d: path("M6 22V2h12v20z");
}

</style>
