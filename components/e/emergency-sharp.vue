<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ph3glsp7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:emergency-sharp" /></template>
<style>
.ph3glsp7n {
  fill: currentColor;
  d: path("M10.75 20.5v-6.315l-5.477 3.167l-1.25-2.179L9.5 12L4.023 8.852l1.25-2.179l5.477 3.168V3.5h2.5v6.34l5.477-3.167l1.25 2.179L14.5 12l5.477 3.173l-1.25 2.179l-5.477-3.168V20.5z");
}

</style>
