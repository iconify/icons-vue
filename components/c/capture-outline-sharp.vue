<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbuxcbczx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:capture-outline-sharp" /></template>
<style>
.cbuxcbczx {
  fill: currentColor;
  d: path("M6.192 15.808h11.616V8.192H6.192zM3 19V5h18v14zm1-1h16V6H4zm0 0V6z");
}

</style>
