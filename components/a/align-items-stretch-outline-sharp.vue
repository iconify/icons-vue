<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bo4pait0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:align-items-stretch-outline-sharp" /></template>
<style>
.bo4pait0c {
  fill: currentColor;
  d: path("M7.5 17.5v-11h2v11zm7 0v-11h2v11zM3 4V3h18v1zm0 17v-1h18v1z");
}

</style>
