<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9mg90h5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:align-justify-stretch" /></template>
<style>
.r9mg90h5a {
  fill: currentColor;
  d: path("M20 21V3h1v18zM3 21V3h1v18zm9.5-11.5v-2h5v2zm-6 0v-2h5v2zm6 7v-2h5v2zm-6 0v-2h5v2z");
}

</style>
