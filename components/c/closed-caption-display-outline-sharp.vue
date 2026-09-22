<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nsybbqpzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:closed-caption-display-outline-sharp" /></template>
<style>
.nsybbqpzd {
  fill: currentColor;
  d: path("M5 18V6zm1.692-8.692v5.384h3.25v-.884H7.577v-3.616h2.615v.616h.885v-1.5zm6.231 0V12.5h.885v-2.308h2.615v.616h.885v-1.5zM4 19V5h16v7.5h-1V6H5v12h4.942v1zm8.327 2v-6.115H21V21zm1-1H20v-4.115h-6.673z");
}

</style>
