<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pw18fr2sf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:4mp-sharp" /></template>
<style>
.pw18fr2sf {
  fill: currentColor;
  d: path("M12.712 11.192h.884v-1.5h1v-.884h-1v-3h-.884v3h-2.116v-3h-.884v3.884h3zm-6.404 7h.884v-4.5h1.616v3h.884v-3h1.616v4.5h.884v-5.384H6.308zm7.5 0h.884v-1.5h3v-3.884h-3.884zm.884-2.384v-2.116h2.116v2.116zM4 20V4h16v16z");
}

</style>
