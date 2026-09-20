<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k7hptl2mh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:align-horizontal-center-outline-sharp" /></template>
<style>
.k7hptl2mh {
  fill: currentColor;
  d: path("M11.5 21v-4.692H7v-2.039h4.5V9.731H4V7.692h7.5V3h1v4.692H20v2.039h-7.5v4.538H17v2.039h-4.5V21z");
}

</style>
