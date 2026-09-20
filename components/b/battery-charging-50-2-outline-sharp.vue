<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4-z3vmrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-charging-50-2-outline-sharp" /></template>
<style>
.x4-z3vmrx {
  fill: currentColor;
  d: path("M2.5 16.5v-9h12.962l-.812 1H9.5v7h5.154l-.177 1zm14.867 0l.604-3.712h-2.933L18.417 7.5h.217l-.604 3.712h2.933L17.585 16.5z");
}

</style>
