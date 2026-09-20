<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ao849hbih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:dialogs-sharp" /></template>
<style>
.ao849hbih {
  fill: currentColor;
  d: path("M8 16h8V8H8zm-5 5V3h18v18z");
}

</style>
