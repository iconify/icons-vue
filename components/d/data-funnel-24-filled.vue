<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pyxlc7bof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:data-funnel-24-filled" /></template>
<style>
.pyxlc7bof {
  fill: currentColor;
  d: path("M19.248 7.504a2.752 2.752 0 0 0 0-5.504H4.75a2.752 2.752 0 1 0 0 5.504zm-2 7a2.752 2.752 0 1 0 0-5.504H6.75a2.752 2.752 0 0 0 0 5.504zM17 18.752A2.75 2.75 0 0 0 14.248 16H9.75a2.752 2.752 0 0 0 0 5.504h4.498A2.75 2.75 0 0 0 17 18.752");
}

</style>
