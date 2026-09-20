<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vbnz0zbzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrow-drop-down-outline-sharp" /></template>
<style>
.vbnz0zbzx {
  fill: currentColor;
  d: path("M12 14.308L8.192 10.5h7.616z");
}

</style>
