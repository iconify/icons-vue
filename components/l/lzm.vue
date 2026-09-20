<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sho87rbzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lzm" /></template>
<style>
.sho87rbzm {
  fill: var(--svg-color--36a4de, #36a4de);
  d: path("M7.2 13.02L3 6.9v13.8h12l-2.7-3.6H7.2zm.6-9.72l4.5 7.5l4.5-7.5H21v17.4h-4.2V9.9l-4.5 7.2L3 3.3z");
}

</style>
