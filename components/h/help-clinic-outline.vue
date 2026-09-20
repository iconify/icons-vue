<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="esjr3zbzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:help-clinic-outline" /></template>
<style>
.esjr3zbzg {
  fill: currentColor;
  d: path("M11 17h2v-5h-2zm1.713-7.288Q13 9.425 13 9t-.288-.712T12 8t-.712.288T11 9t.288.713T12 10t.713-.288M4 21V9l8-6l8 6v12zm2-2h12v-9l-6-4.5L6 10zm6-6.75");
}

</style>
