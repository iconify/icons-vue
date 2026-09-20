<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jf49pknzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:dialogs-sharp" /></template>
<style>
.jf49pknzu {
  fill: currentColor;
  d: path("M9 15h6V9H9zm-5 5V4h16v16z");
}

</style>
