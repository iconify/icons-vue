<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gn7jahb2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:amp-stories-outline-sharp" /></template>
<style>
.gn7jahb2u {
  fill: currentColor;
  d: path("M7 20V4h10v16zm-4-2V6h2v12zm16 0V6h2v12zM9 18h6V6H9zm0 0V6z");
}

</style>
