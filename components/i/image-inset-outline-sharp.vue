<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ipx9ljbzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:image-inset-outline-sharp" /></template>
<style>
.ipx9ljbzd {
  fill: currentColor;
  d: path("M6 16h12V8H6zm2-2l2.125-2.825L11.5 13l1.875-2.5L16 14zm-6 6V4h20v16zm2-2h16V6H4zm0 0V6z");
}

</style>
