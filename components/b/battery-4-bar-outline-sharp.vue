<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nd16z6bmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-4-bar-outline-sharp" /></template>
<style>
.nd16z6bmy {
  fill: currentColor;
  d: path("M9 12h6V6H9zM7 22V4h3V2h4v2h3v18z");
}

</style>
