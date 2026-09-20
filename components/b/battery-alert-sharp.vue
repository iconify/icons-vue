<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w51io5bbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-alert-sharp" /></template>
<style>
.w51io5bbb {
  fill: currentColor;
  d: path("M7 22V4h3V2h4v2h3v18zm4-8h2V8h-2zm1 4q.425 0 .713-.288T13 17t-.288-.712T12 16t-.712.288T11 17t.288.713T12 18");
}

</style>
