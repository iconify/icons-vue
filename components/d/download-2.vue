<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="domfhibts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:download-2" /></template>
<style>
.domfhibts {
  fill: currentColor;
  d: path("M4 22v-2h16v2zm8-4L5 9h4V2h6v7h4z");
}

</style>
