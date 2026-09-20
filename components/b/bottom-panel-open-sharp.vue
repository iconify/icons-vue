<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ohk9dkb-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bottom-panel-open-sharp" /></template>
<style>
.ohk9dkb-k {
  fill: currentColor;
  d: path("M8 11.5h8l-4-4zM5 14h14V5H5zm-2 7V3h18v18z");
}

</style>
