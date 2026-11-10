<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hddsa_bgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:guidepoint-sharp-fill" /></template>
<style>
.hddsa_bgb {
  fill: currentColor;
  d: path("M19 8C21.209 8 23 9.79 23 12C23 14.21 21.209 16 19 16C17.362 16 15.954 15.01 15.336 13.6L15.223 13.32L15.127 13H8.872C8.398 14.68 6.831 16 5 16C2.791 16 1 14.21 1 12C1 9.79 2.791 8 5 8C6.831 8 8.398 9.32 8.872 11H15.128C15.602 9.32 17.169 8 19 8Z");
}

</style>
