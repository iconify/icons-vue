<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vq29xabcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:exposure-neg-1" /></template>
<style>
.vq29xabcs {
  fill: currentColor;
  d: path("M9.5 13.385h-6v-1h6zm6.827 4.577V7.473l-2.53 1.766l-.574-.827l3.37-2.373h.791v11.923z");
}

</style>
