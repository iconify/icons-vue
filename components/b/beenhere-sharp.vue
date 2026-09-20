<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="asyf0_qyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:beenhere-sharp" /></template>
<style>
.asyf0_qyh {
  fill: currentColor;
  d: path("m12 21.77l-7-5.25V3h14v13.52zm-1.05-7.462l4.958-4.958l-.708-.72l-4.25 4.25l-2.138-2.138l-.72.708z");
}

</style>
