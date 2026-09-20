<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwcoexbss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:align-justify-center-outline" /></template>
<style>
.dwcoexbss {
  fill: currentColor;
  d: path("M11 22V2h2v20zm4-5V7h3v10zm-9 0V7h3v10z");
}

</style>
