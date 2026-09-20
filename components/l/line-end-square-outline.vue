<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oldmkuwnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:line-end-square-outline" /></template>
<style>
.oldmkuwnp {
  fill: currentColor;
  d: path("M13 15.5h7v-7h-7zm-2 2V13H2v-2h9V6.5h11v11zm5.5-5.5");
}

</style>
