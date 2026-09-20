<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eiuzuc-3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:h-plus-mobiledata-badge-sharp" /></template>
<style>
.eiuzuc-3w {
  fill: currentColor;
  d: path("M5.308 16.5h1v-4h4.615v4h1v-9h-1v4H6.308v-4h-1zm10.384-2h1v-2h2v-1h-2v-2h-1v2h-2v1h2zM2 20V4h20v16z");
}

</style>
