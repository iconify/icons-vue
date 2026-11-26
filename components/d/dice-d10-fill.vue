<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q02l_zb5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:dice-d10-fill" /></template>
<style>
.q02l_zb5c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.1213 18.1213L14.1213 22.1213C13.5587 22.6839 12.7956 23 12 23C11.2044 23 10.4413 22.6839 9.8787 22.1213L1.8787 14.1213C1.3161 13.5587 1 12.7956 1 12C1 11.2044 1.3161 10.4413 1.8787 9.8787L9.8787 1.8787C10.4413 1.3161 11.2044 1 12 1C12.7956 1 13.5587 1.3161 14.1213 1.8787L22.1213 9.8787C22.6839 10.4413 23 11.2044 23 12C23 12.7956 22.6839 13.5587 22.1213 14.1213ZM3 13L7 13L7 11L3 11ZM17 13L21 13L21 11L17 11ZM11 17L11 21L13 21L13 17ZM10.9285 7.3714L12 4.6926L14.8266 11.7592L12 14.5858L9.1734 11.7592Z");
}

</style>
